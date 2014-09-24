---
layout: post
title:  "Cumulus.af - Unlimited cloud storage hack"
date:   2014-01-01 18:59:58
categories: code storage dropbox
---

[**Cumulus.af**][node] was a hackathon project done at HackMIT Fall 2013. The application exploits dropbox's API, and URL accessible storage scheme. The result is an application that abstracts storage and across mutliple free accounts. Functionality for fragmenting large files (like 100GB) across multiple dropbox accounts was in the works. The project was written in Node.JS which had shaky dropbox API support. The project has been translated by a classmate to Python for better dropbox interop. The new version, called Monsoon, can be found [**here**][python].

The original source code can be found [**here**][node].

[node]: https://github.com/unblevable/cumulus.af
[python]: https://github.com/raymondjacobson/monsoon
