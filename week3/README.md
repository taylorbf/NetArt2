# Week 3: Making your own JS library

- Familiarize yourself with [npm](https://www.npmjs.com/) and [bower](http://bower.io/)
- Look especially at [creating node modules](https://quickleft.com/blog/creating-and-publishing-a-node-js-module/) and [creating bower packages](http://bower.io/docs/creating-packages/)
- Try installing and using a few bower packages, just to see how they're used.

### Exercise

In this week3 folder there is code for querying a google image search. This code is lifted from a neat web art project [1984](http://popsnorkle.com/works/1984/1984.html), which I'm sure lifted it from somewhere else.

Since this code seems useful, I'd like you to make a barebones js library which wraps this code. Then, publish it as an node module or, more likely, a bower package. This is primarily to practice making a publishable libary.

The end result then, is that someone could write `bower install googleimg` (or similar) and have access to your library. Then, they should be able to link to your js file and have some way of calling your code through an API that you provide in your Readme. 

Your API only needs to have a function or two. It's up to you what kind of parameters you want to afford. The goal is a very basic practice module.
