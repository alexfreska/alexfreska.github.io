---
layout: post
title:  "Grapefruit - A modern replacement for blackboard"
date:   2014-02-09 18:59:58
categories: code blackboard lms
---

[**Grapefruit**][gf] is a modern, open source, replacement for Blackboard. Currently Grapefruit is being developed at Rensselaer where it is slowly being transitioned into use. Blackboard is closed source, insanely expensive, and and lacks quality from both engineering and user experience perspectives. Blackboard is rarely used in the way it intends and is inherently non-intuitive. Grapefruit aims to create an excellent user experience for both students and teachers.

My role on the Grapefruit team is implementing modern front-end design. I am implementing frontend interfaces using React, a library that harnesses the power of a virtual dom, state based components, and one-way data flow. Using React leads to much more expressive and pure code. As projects grow typical MVC architectures can cause nightmares tracking down hidden sources of data mutation and state.

<img src="{{site.url}}/assets/grapefruit.png" alt="template" style="width: 100%;"/>

The source code can be found [**here**][gf].

[gf]: https://github.com/grahamcracker/Grapefruit
