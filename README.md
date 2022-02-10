# Bogan Ipusm

[![Scc Count Badge](https://sloc.xyz/github/boyter/boganipsum/)](https://github.com/boyter/boganipsum/)

The new an improved!(?) bogan ipsum because boganipsum.com fell of the face of the earth and this needed to exist again. https://boganipsum.com.au/

Everything is MIT licensed because the library which was used to get the first working version was. I don't really do fancy builds for simple things like this so it's a copy of that turned into old school JS. The library is https://github.com/rvagg/node-boganipsum if you are curious.

## Build Instructions

It's a HTML page, there are none. Just edit it and save. Means you can have a local copy too! Deploy you own bogan ipsum and we can add the link somewhere in this document as a mirror.

PR's are accepted.

## Deployment

Deployment is `git pull --rebase && scp index.html root@boyter.org:/var/www/boganipsum/` but you need access to my server which isn't going to happen, so just add a PR or something if you want it released.
