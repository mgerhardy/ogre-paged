![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen1.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen1.jpg)

  * **Description**: Real-time rendering of massive, dense forests, with not only trees, but bushes, grass, rocks, and other "clutter". Supports dynamic transitioned LOD between batched geometry and static impostors (extendable).
  * **License**: [zlib/libpng](http://www.opensource.org/licenses/zlib-license.php) (free for any use)
  * **Author**: John (JohnJ) Judnich
  * **Current Maintainer**: Thomas Fischer (tdev)
  * **Bugtracker / Issue Ticket system / Support**: [see Issues Tab](http://code.google.com/p/ogre-paged/issues/list)
  * **Supported Platforms**: Windows, Linux, (Mac)
  * **Supported Ogre Releases**: >= 1.6
  * **Documentation: API Documentation, Tutorials, Examples**: (included in [downloads](http://code.google.com/p/ogre-paged/downloads/list))
  * **Sources**: [see Source tab](http://code.google.com/p/ogre-paged/source/checkout)
  * **Product Support & News & Discussion Forum**: [PagedGeometry Addon Forum](http://www.ogre3d.org/phpBB2addons/viewforum.php?f=14)


## What is PagedGeometry? ##
The PagedGeometry engine is an add-on to Ogre which provides highly optimized methods for rendering massive amounts of small meshes, covering a possibly infinite area. This is especially well suited for dense forests and outdoor scenes, with millions of trees, bushes, grass, rocks, etc., etc.

Paged geometry gives you many advantages over plain entities, the main one being speed: With proper usage of detail levels, outdoor scenes managed by PagedGeometry can be >100x faster than plain entities. Another advantage is that the geometry is paged; in other words, only entities which are immediately needed (to be displayed) are loaded. This allows you to expand the boundaries of your virtual world almost infinitely (only limited by floating point precision), providing the player with a more realistically scaled game area.


## Features ##
**Complete API documentation included, describing every feature in detail** 4 tutorials included to teach you how to get PagedGeometry set up and optimized in your project
**7 examples included to demonstrate the actual use of various selected features** Dynamic geometry paging system, which enables infinite worlds
**Batched rendering [[LOD](LOD.md)] for optimized rendering of near-by trees** Impostor rendering LOD for extremely fast rendering of distant trees
**Flexible LOD display system, which can be expanded to display geometry with any technique you can implement** Flexible LOD configuration system, which allows you to configure any combination of supported LODs in any way you want
**Optional cross-LOD fade transitions, and far LOD fade-out, fully configurable** Flexible PageLoader system, allowing you to dynamically load geometry from any source you can imagine
**Easy addition / removal of trees with bit packing, allowing millions of trees to be stored in RAM using only a few MBs** Color-map support for trees, which enables you to apply terrain lightmaps to your trees with one simple function call
**Animated, optimized grass rendering system. Supports density maps, color maps, wind animations, height range restriction, and much more.**


## Download PagedGeometry ##
> see the "Downloads" Tab: http://code.google.com/p/ogre-paged/downloads/list

Includes tutorials, examples, and API documentation.

After downloading PagedGeometry, read "GettingStarted.txt", which will help you make sure everything is set up properly for PagedGeometry to run.

**Note:** If you want to get the absolute latest "development" release of PagedGeometry, you can find it in the ogreaddon SVN under "forests", or use the following SVN root:


#### Screenshots & Videos ####

###### Recent Screenshots ######

Expansive jungle scene with 240,000 trees and animated vegetation, running at 100 - 150 FPS on a GeForce 7800 GT:

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryScreen1.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryScreen1.jpg)

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryScreen2.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryScreen2.jpg)

Note: More screenshots from this scene can be seen in Ogre's [Featured Project Gallery](http://www.ogre3d.org/index.php?set_albumName=album53&option=com_gallery&Itemid=55&include=view_album.php).

Detailed forest scene with trees, ferns, mushrooms, flowers, etc., running at ~100 FPS on a GeForce 7800 GT:

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen1.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen1.jpg)

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen2.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen2.jpg)

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen3.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen3.jpg)

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen4.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen4.jpg)

![http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen5.jpg](http://www.ogre3d.org/tikiwiki/img/wiki_up/PagedGeometryForestScreen5.jpg)


###### Videos (Slightly Outdated) ######

[Jungle Video](http://www.alsbonsai.com/john/Jungle.wmv) (5.53 MB, WMV Format)

[Vast Forest Video](http://www.alsbonsai.com/john/Vast.wmv) (5.62 MB, WMV Format)

[Grass Shadows Video](http://www.alsbonsai.com/john/GrassShadows.wmv) (3.72 MB, WMV Format)

###### Old Screenshots ######

[Forest Screenshot 1](http://www.alsbonsai.com/john/Opt2.jpg)

[Forest Screenshot 2](http://www.alsbonsai.com/john/Forest4.jpg)

[Forest Screenshot 3](http://www.alsbonsai.com/john/Opt.jpg)

[Jungle Screenshot 1](http://www.alsbonsai.com/john/Jungle1.jpg)

[Jungle Screenshot 2](http://www.alsbonsai.com/john/Jungle2.jpg)

[Jungle Screenshot 3](http://www.alsbonsai.com/john/Jungle3.jpg)

[Grass Screenshot 1](http://www.alsbonsai.com/john/Grass1.jpg)

[Grass Screenshot 2](http://www.alsbonsai.com/john/Grass2.jpg)

###### Old Videos ######

[Tree Demo Video](http://www.alsbonsai.com/john/PagedGeometry2.wmv) (5.27 MB, WMV Format)

[Grass Demo Video](http://www.alsbonsai.com/john/GrassVideo.wmv) (4.49 MB, WMV Format)
