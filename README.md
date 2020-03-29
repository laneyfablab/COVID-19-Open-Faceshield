# LaneyShield
## Rapidly produced faceshields for health care workers
[See our website for more information](https://www.laneyshield.laneyfablab.org/)

# [Newest release here](https://github.com/laneyfablab/LaneyShield/releases)

Health care workers need faceshields now. The Laney FabLab has created the LaneyShield, a faceshield that can be rapidly produced using 4 components and with common industrial materials.

## Prerequisites for prototyping
Software
- [Autodesk Fusion 360](https://www.autodesk.com/products/fusion-360/overview)
- [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) or other 2D vector editing software such as [Inkscape](https://inkscape.org/) or [Corel Draw](https://www.coreldraw.com/en/)

Hardware
- Laser cutter
- CNC mill with drag knife for small scale manufacture
- Basic shop tools

## Bill of materials (BOM)

| Quantity   |      Item      |  Material |  Specification |  McMaster  |
|----------|:-------------:|:-------:|:----:|:---:|
| 1 |  Shield | PET |  ~120 sq in | https://www.mcmaster.com/8567k64 |
| 1 |    Foam   |  Polyurethane |  1.125" x 8"  | https://www.mcmaster.com/8614k84
| 1 | Strap |    Nylon | 1" x 19"  |  https://www.mcmaster.com/88225k68  |
| 1 | Staple |    Steel | Common staple  |    |

## Drawings
![Shield Technical Drawing](https://github.com/laneyfablab/LaneyShield/blob/master/img/shieldDrawing.png "Shield Technical Drawing")

![Foam Technical Drawing](https://github.com/laneyfablab/LaneyShield/blob/master/img/foamDrawing.png "Foam Technical Drawing")


## Development notes

This design is based off the face shield design from [Delve](https://www.delve.com/insights/face-shield-designs-to-fill-the-gap), a design firm in Wisconsin. Their design is being used at hospitals in their region with much success. Our design adds slots to the right side of the shield, allowing for adjustability and comfort.

## Prototyping process

We used Fusion 360 to model the original Delve design. We used strict parameters on all the specifications of our design. We exported DXFs from base geometry and laser cut the shields with different slot sizes. We agreed that a slot size of 0.125" wide by 0.75" high made for an adjustable but secure fit for the nylon strap. We cut polyurethane foam at various widths and lengths to find the correct specification, which is 1.125" wide by 8" long.

## Our current stage of development

We are developing a fixture jig to help assembly of the straps in the slots. That fixture jig may affect the length of the foam piece. We will prototype this fixture and begin iterating on assembly techniques on Monday 3/3/20. Non latex straps need to be sourced for workers with latex allergies.
