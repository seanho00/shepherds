# reveal-skel

[![Travis-CI build status](https://travis-ci.org/sermons/reveal-skel.svg)](https://travis-ci.org/sermons/reveal-skel)
[![Node dependencies](https://david-dm.org/sermons/reveal-skel.svg)](https://david-dm.org/sermons/reveal-skel)
[![Node dev status](https://david-dm.org/sermons/reveal-skel/dev-status.svg)](https://david-dm.org/sermons/reveal-skel#info=devDependencies)

Template presentation using Reveal.js

First draft generated by Yeoman and
[generator-reveal](https://github.com/slara/generator-reveal)

I tweaked sone Reveal.js options, added style sheet, etc., and a Travis config to deploy to Github Pages.

## Usage
* Fork this project
* Use your own deploy key:
	* ssh-keygen
	* travis encrypt-file
* Slide content goes in `slides`, in particular, `slides/index.md`.
* Static assets (CSS, JS, images, etc) go in `static`, the grunt task will copy this dir as-is to the deploy directory.
