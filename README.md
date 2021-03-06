BDX
===

BDX is a small 3D game engine, designed to work with [Blender](http://www.blender.org/) (as an addon), and built to leverage [libGDX](http://libgdx.badlogicgames.com/), along with the [Bullet physics library](http://bulletphysics.org/) (specifically, the [gbullet](http://code.google.com/p/gbullet/) port). It features a straightforward execution model, supported by a relatively simple API, enabling the programmer to effectively define object behavior within a typical blender scene.

From a "build and deploy" perspective, BDX projects are simply extended libGDX projects, which means that you can use the same gradle-powered pipeline to deploy BDX games to any platform that's currently supported by libGDX (Windows, Linux, Mac OS X, HTML5, Android and iOS).

License
-------

BDX is licensed under the permissive [Apache 2 License](http://www.apache.org/licenses/LICENSE-2.0.html) (just like libGDX): You can use this software free of charge, no strings attached, in commercial and non-commercial projects.

Dependencies
------------

For game development with BDX, you only need a relatively recent version of the Java Development Kit (I tested with 1.7).

If you plan on developing the engine itself, you'll additionally need a working version of [ant](http://ant.apache.org/).

Download and Install
--------------------

You can find the latest release [here](https://github.com/GoranM/bdx/releases).

Download bdx.zip. Once you have it, you can install it like any other blender addon - In User Preferences, click on the "Install from File" button, then find and install bdx.zip.

After that, you just need to enable it (you can find it in the Import-Export category - Testing support level), and then Save User Settings, so you don't have to re-enable after every blender restart.

At that point, there should be a BDX panel in the Render properties window.

Use
---

You can find relevant information in [the wiki](https://github.com/GoranM/bdx/wiki).
