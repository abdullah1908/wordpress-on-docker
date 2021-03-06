# WordPress via Docker
This repository provides a ready-to-use WordPress setup on Docker, perfect for quickly jumping into a new theme/plugin development.

![](https://i2.wp.com/www.davideguida.com/wp-content/uploads/2017/06/dockerPress.png?resize=788%2C227&ssl=1)

## Theme deployment
It includes 2 starter themes : 
- one from [underscores.me](http://underscores.me/)
- one from [WordPress Gulp Starter Kit](https://github.com/xsynaptic/wordpress-gulp-starter-kit) which includes a full gulp-based development workflow.
Just pick the one you like best and start hacking. 

## Plugin development
It includes an instance of the [WordPress Plugin Boilerplate](http://wppb.io/)
You could also [generate one here](https://wppb.me/).

## Installation
- [install Docker](https://docs.docker.com/install/)
- [install Docker-compose](https://docs.docker.com/compose/install/)
- Clone this repository on your computer

## How-to use it
- `cd` to your project folder
- Start the machine: `docker-compose up -d`
- Visit http://localhost:1973/ to see the live local site.
- Visit http://localhost:8080/ to use PhpMyAdmin and perform database dumps (obligatory in between docker reloads, otherwise you will lose any change in the database).
- To stop the machine: `docker-compose down`

## potential future improvements
- provide a gulpfile.js in the my-plugin folder, tailormade for easying WordPress plugin development.
- change the wp-content to a setup closer to roots.io/bedrock. 
