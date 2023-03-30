# SimpleStackTrace
A cross platform intended Stack Trace and Exception handling Library developed for C++14 with the idea of it being simple and quick to use as a plug and play, also being C++14 it is possible to use in consoles and several game engines. 

## Why
---

Because I'm ugly sick that there is no library dedicated to stack tracing that is actually lightweighted and efficient


### There are other alternatives already on the internet, why this?
Most of the libraries I have found are either dependent of a lot of things that are either
outdated, heavy, complicated or an overkill to use, and not really nice to use when you
start looking at the insides of them. Also some of them need you to have the application
running on RTTI and such specs that may not be the cup of tea of everyone. This tool is intended to be as independent of everything as possible.


### But there's BOOST! Why not use it?

_"Yeah, sure, and also shoot myself in the foot while I'm at it, right?"_

To be honest, BOOST is not that bad, but using BOOST **ONLY** for stack tracing is overkill because of how it works when it comes to dependencies.
The library asks you for a header that needs another header that needs another header...
until you end up downloading all of the BOOST library instead of only what you were looking for,
and that ain't something nice in my opinion. If you like BOOST and it works for you, 
fine, you are on your right to like it. This library was intended to be independent of other
implementations or modules of the application.
