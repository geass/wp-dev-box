# Wordpress Contributor Box (WP-DEV-BOX)

WP-DEV-BOX is created to prepare an enviroment for contributors.

  - Only pull it, and set your enviroment
  - Solve the issues!
  - Contribute the wordpress besides OPEN-SOURCE WORLD

Why there is a project like that ?
  - Whether you have linux or not, start a new enviroment always hard stuff for lazy ones
  - We love the DEVOPS!
  - nothing more

### Version
0.1

### Tech

WP-DEV-BOX uses a number of open source projects to work properly:

##### Provisioning

* Nginx
* MySql
* Php7

##### Deployment

* [Ansible] - Best of deployment/provisioning library
* [Vagrant] - Best of virtualization technology
* [Wordpress] - Best of open-source CMS
* ... nothing more uh-oh

And of course WP-DEV-BOX itself is open source with a public repository
 on GitHub.

### Installation

We love the DevOps, and we believe the automation so we are trying our best. On wp-dev-box project, your requirement only pulling the repo and makine the vagrant up with some parameters. We are believing, one day we will do all of these steps with only your a few words, by the way to that time, may you pull on yourself?

```sh
$ git clone https://github.com/geass/wp-dev-box
$ cd wp-dev-box/platform
$ vagrant --ip=192.168.38.10 --path=/your/local/path/where/wordpress/will/be/cloned up
```

after that only to do add "wordpress.deev" and your box ip to your etc/hosts file.

```sh
$ nano /etc/hosts (for *nix sistems)
````
/etc/hosts:
```sh
192.168.38.10 wordpress.dev
```
Note: No need to clone wordpress, we are doing too!

Go to wordpress.dev, make some simple installation and do your contributions!

### Development

Want to contribute? Great!

Found a bug or wants to create a new feature on wp-dev-box, great! follow this steps, and commit us!

Open your favorite Terminal and run these commands.

```sh
$ git checkout-b feature-branch-name
$ git add . (or add the changed files)
$ git commit -m "your commit message what u did?"
$ git push -u origin feature-branch-name
```

