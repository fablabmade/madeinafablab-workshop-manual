# Digital Fabrication for Local Production

## Digital design

The design is a file in the computer

Design can be transferred

Scale is not a problem

You have a great choice of tools and processes for production

## Machines controlled by the computer

What is the difference

G-code is the code used by machines to receive instructions from the computer.

For 3D printers the G-Code is produced by a Slicing software, for CNC Mills by a CAM software, and for the others by specific applications.

G-Code looks like this:

    O8001
    N10 (Digit "1")
    N20 (AUTHOR - NAME)
    N30 G00 X[#502*0.5+#500] Y[#502*1.0+#501] Z[#503+0.2]
    N40 Z[#503+0.05]
    N50 G01 Z[#503-#504]
    N60 Y#501
    N70 G00 Z[#503+0.2]
    N80 M99

i.e. G0 is the command to move the machine head

## Technologies & Processes 

Digital Fabrication means building objects out of digital designs. What this means in practice is more complex.

In many cases we need to use a combination of machines and processes to actually build a functional object out of any digital design.

Some parts, maybe made in plastic, will be 3D printed, while some other will use metals such as aluminium, machined by a CNC Mill. For the packaging we might use the Laser cutter to cut custom cardboard boxes, and the vynil cutter for adding graphics.

The list below provides an overview of different technologies commonly found in fablabs, and some others which are slowing being adopted at scale.

3D Printing

- [FDM](https://en.wikipedia.org/wiki/Fused_deposition_modeling)
- [SLS](https://en.wikipedia.org/wiki/Selective_laser_sintering)
- [SLA](https://en.wikipedia.org/wiki/Stereolithography)
- [Metals](https://3dprint.com/wp-content/uploads/2016/01/3dp_HP_MultiJetFusion_chart-e1451937857395.jpg)

Laser cutting & engraving

- [co2](), [fiber](), [neodimium]()
- cutting organic materials, most of the plastics, fabric
- engraving metal, stone, ceramics

Vinyl cutting

- [stickers](https://www.sprinter.com.sg/wp-content/gallery/die-cut-sticker/die-cut-stickers_1.jpg)
- [transfer](https://i1.wp.com/www.laprintanddesign.com/wordpress/wp-content/uploads/2015/04/vinyl_printing_-Los-Angeles.gif)
- [wrapping](https://i.pinimg.com/736x/bf/77/c7/bf77c78e69aa72022319c737b63fc54b.jpg)

Milling 

- [precision](http://www.hlpmc.com.tw/wp-content/uploads/2014/12/en_aerospace04.jpg)
- [large format](https://i.ytimg.com/vi/iszvfWS60A0/maxresdefault.jpg)
- [pcb](http://timeguy.com/cradek-files/cnc/pcb/dscn6119.jpg)

Molding and casting

- [silicon](http://www.bluemaize.net/im/arts-crafts-sewing/silicone-mold-6.jpg)
- [concrete](https://static.concretenetwork.com/photo-gallery/images/550x412Exact_0x4/site_26/smooth-on_2183.jpg)
- [sand](http://www.onallcylinders.com/wp-content/uploads/2016/07/15/05-1600x1067.jpg)
- [chocolate](https://img.leafcdn.tv/640/ppds/8ec0cee8-d2ce-4001-a177-23e185426206.jpg)

Injection molding

- [silicon mold - desktop injection](http://www.rapidreadytech.com/wp-content/uploads/2013/06/Plastic-Injection-Molding.jpg)
- [metal mold - large scale](https://upload.wikimedia.org/wikipedia/commons/2/2a/LegoSpritzguss.JPG)

Metal casting
- [delft clay casting](http://sandrasavelli.nl/wp-content/gallery/mainpage/IMG_5288-2-1024x768.jpg)
- [aluminium casting](https://i.pinimg.com/originals/3f/c3/63/3fc363beed54913d6d781a32c2119ec5.jpg)
- [precious metal casting](http://www.siaai.com/content/wp-content/flgallery/images/m9k124s60r8o.jpg)

Plasma, EDM, Waterjet
- [Plasma](https://www.lanteksms.com/media/uploads/solution/sheet-metal-plasma.jpg)
- [EDM](http://www.milcowireedm.com/images/diverse_capabilities.jpg)
- [Waterjet]()http://www.aquajetllc.com/images/Stacked-Material-Cut-by%20Water-Jets.jpg

Termoforming
- [small scale](http://justindunham.net/images/uploads/2011/07/IMG_2742.jpg)
- [industrial](http://www.plasticsnews.com/apps/pbcsi.dll/storyimage/PN/20150225/NEWS/150229963/AR/0/SencorpWhite-thermoforming-NPE-2015.jpg)



