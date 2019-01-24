---
layout: post
author: Henry Ma
---

> __"I would not give a fig for the simplicity on this side of complexity, but I would give my life for the simplicity on the other side of complexity."__

## Germination

> Back to the very first days of becoming an indie maker, starting to build web-based MVP(Minimum Viable Product), I quickly found myself in need of __JSON Storage (as a ) Service__ which is:   
* Lightweight on setup, use and maintain
* API【Out-of-the-box】
* Production ready
* Better to have offline support
* Better to have decentralized networking support
* Better to be open source
* Free

## Wonderlands being explored

* [JSON@Github](https://github.com/search?o=desc&q=json&s=stars&type=Repositories)
* ["JSON Store"@Google](https://www.google.com/search?newwindow=1&ei=9DZJXPvpEovy8AXT9ohY&q=%22JSON+store%22&oq=%22JSON+store%22)

## Candidates

* [JSON-Server](https://github.com/typicode/json-server): Get a full fake REST API with zero coding in less than 30 seconds (seriously)
> Focusing on serving prototyping and mocking, thus seems like not very fit for production use. eg, FileAsync for concurrency not supported yet in node version???
* [lowdb](https://github.com/typicode/lowdb): Small local JSON database powered by Lodash (supports Node, Electron and the browser)
> The storage layer behind JSON-Server.
* [JSONPlaceholder](https://github.com/typicode/jsonplaceholder): A simple online fake REST API server
> Fake Online REST API for Testing and Prototyping 
> Serving ~200M requests per month 
> Powered by JSON Server + LowDB
* [jsonstore.io](https://www.jsonstore.io): Free and secured JSON-based cloud datastore for small projects
* [JSONbin.io](https://jsonbin.io) | Free JSON storage service and JSON hosting service.
> Additional(>10,000 requests) needs payment
* [jsonbin.org](https://jsonbin.org)
> Currently in beta
* [Kinto](https://github.com/Kinto/kinto): A generic JSON document store with sharing and synchronisation
> Powered by Mozilla and its ecosystem, pretty good overall experience based on current experimental usage, a little bit heavy mainly due to design.
* [Gun](https://github.com/amark/gun): A realtime, decentralized, offline-first, mutable graph database engine
* [Automerge](https://github.com/automerge/automerge): A JSON-like data structure (a CRDT) that can be modified concurrently by different users, and merged again automatically
* [OrbitDB](https://github.com/orbitdb/orbit-db) : Peer-to-Peer Databases for the Decentralized Web

## Conclusions

* For __prototyping and mocking__, especially as __front-end developers__, __JSON-Server/JSONPlaceholder__ suite would be the best choice.
* For __production ready__ JSON store as a service
> * __Lightweight__? Go with __lowdb__
> * __Generic and Reuse__? Go with __Kinto__
> * __Simple and Hosted__? __Try__ jsonstore.io/jsonbin.io/jsonbin.org and __choose__.
* For __decentralization__ solution, Gun/Automerge/OrbitDB all seem like good ones.
> __Would probably go back for a update once getting more practical experieces. :whale:__