---
title: "Web Application with Rust and ReasonML: Overview"
date: "2019-03-31T09:24"
---

The landscape of technologies to build web applications has been rapidly changing over the last couple of years. There are more technologies coming out that will drastically change what we can do in web applications in a profound way. Recently I've been thinking about a lot of the new ways that people have been coming up with to build on the web with and I wanted to explore what building a complete application in these new technologies would be like. Specifically I'll be exploring building a web application using ReasonML with WebAssembly and Rust. 

### ReasonML

If you haven't heard of [ReasonML](https://reasonml.github.io/) before, it's a special syntax on top of the OCaml language that was developed at Facebook. It makes the syntax of OCaml something more familiar to those with a JS background while keeping all of the benefits of the OCaml type system and allows you to compile your Reason code to JavaScript. To pull right from their website: _Reason lets you write simple, fast and quality type safe code while leveraging both the JavaScript & OCaml ecosystems._ If you would like to learn more about ReasonML check out this [video](https://www.youtube.com/watch?v=lzEweA7RPi0) by Ken Wheeler or this [blog post](https://jaredforsyth.com/posts/getting-started-with-reason-and-bucklescript/) by Jared Forsyth.

### Rust

 The other main technology we will be focusing on is Rust. Rust is a systems programming language built by Mozilla focused on speed, type safety, and correctness. Rust brings ergonomics and type safety to the world of systems programming. It has an amazing community and eco-system that makes building applications in many diverse environments a joy. You can build everything from low level hardware drivers and operating systems to complete web application frontends in Rust and more. Check out the [Rust lang YouTube channel](https://www.youtube.com/channel/UCaYhcUwRBNscFNUKTjgPFiA/videos) and the [website](https://www.rust-lang.org/) for more info!

### Wrap Up

As exciting as these technologies are I haven't seen many articles or write-ups about using them together to build web applications and my aim is to change that here. Over the next few blog posts in this series we are going to be building a simple Photoshop document editor in the browser with ReasonML and WebAssembly on the frontend and a Rust server on the backend. I hope you all have as much fun learning and working with these technologies as I did pulling this together! 

We would love to have you join the Rust community; come check us out on [Discord](https://discordapp.com/invite/aVESxV8) and [GitHub](https://github.com/rust-lang). If you're specifically interested in web technology in Rust the Rust and WebAssembly team would love you to join us! Checkout our [website](https://rustwasm.github.io/) and get involved! 