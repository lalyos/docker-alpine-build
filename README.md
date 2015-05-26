Static builds are favorable. Its not limited, but very usefull when createing tiny Docker images.
They can be base on `alpine`, or even `scratch`.

> A static build is a compiled version of a program which has been statically linked against libraries.

## Usage

Start you container from `lalyos.alpine-build:edge`
```
FROM lalyos/alpine-build:edge
```

## tl;dr

Alpine linux is ideal for static builds, as its using [musl libc](http://www.musl-libc.org), 
which is a libc implementation focus is to be lightweight and fast:

> Designed from the ground up for static linking, musl carefully avoids pulling in large amounts of code or data that the application will not use. 


