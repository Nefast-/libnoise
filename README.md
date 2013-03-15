libnoise
========

[libnoise](http://libnoise.sourceforge.net/) is a portable C++ library that is used to generate coherent noise, a type of smoothly-changing noise. libnoise can generate Perlin noise, ridged multifractal noise, and other types of coherent-noise.

Coherent noise is often used by graphics programmers to generate natural-looking textures, planetary terrain, and other things. The mountain scene shown above was rendered in Terragen with a terrain file generated by libnoise. You can also view some other examples of what libnoise can do.

In libnoise, coherent-noise generators are encapsulated in classes called noise modules. There are many different types of noise modules. Some noise modules can combine or modify the outputs of other noise modules in various ways; you can join these modules together to generate very complex coherent noise.

About this Fork
---------------

I'm using libnoise, version 1.0.0, in one of my projects and thus had to rebuild libnoise a few times to keep up with the different platforms and dependencies, but since the Makefile of the [original source code](http://libnoise.sourceforge.net/downloads/index.html) for version 1.0.0 is broken, I've decided to create a fork and get libnoise to a modern build system, i.e. CMake. I hope it will be of some help to others as well.

Credits
-------

All the credit goes to the original author: [Jason Bevins](http://libnoise.sourceforge.net/)

Licensing
---------

The library is under the GNU Lesser General Public License (LGPL). For more details see the [COPYING.txt](https://github.com/eXpl0it3r/libnoise/blob/master/COPYING.txt) file.

------------------------------------------------------------------------

Original Information from the Website
=====================================

libnoise is a portable C++ library that is used to generate [coherent noise](http://libnoise.sourceforge.net/glossary/index.html#coherentnoise), a type of smoothly-changing noise. libnoise can generate [Perlin noise](http://libnoise.sourceforge.net/glossary/index.html#perlinnoise), ridged multifractal noise, and other types of coherent-noise.

Coherent noise is often used by graphics programmers to generate natural-looking textures, planetary terrain, and other things. The mountain scene shown above was rendered in [Terragen](http://www.planetside.co.uk/terragen/) with a terrain file generated by libnoise. You can also view some other [examples](http://libnoise.sourceforge.net/examples/index.html) of what libnoise can do.

In libnoise, coherent-noise generators are encapsulated in classes called noise modules. There are many different types of noise modules. Some noise modules can combine or modify the outputs of other noise modules in various ways; you can join these modules together to generate very complex coherent noise.

libnoise is known to compile using the following compilers on the following platforms:

Microsoft Visual C++ 5.0 under Microsoft Windows 2000 Service Pack 4

* gcc 3.3.4 under Gentoo Linux 10.0 (x86)
* gcc 3.x.x under FreeBSD 6 (64-bit SPARC)

From this site, you can [download](http://libnoise.sourceforge.net/downloads/index.html) the following:

* libnoise sources
* libnoise headers
* libnoise binaries
* libnoise documentation

Before using libnoise, you may want to learn more about [coherent noise](http://libnoise.sourceforge.net/glossary/index.html#coherentnoise). You may also want to [learn how coherent noise is generated](http://libnoise.sourceforge.net/noisegen/index.html).

*Note:* libnoise does not generate images, it only generates [coherent-noise](http://libnoise.sourceforge.net/glossary/index.html#coherentnoise) values. It is up to the programmer to use these values to generate images.