# Microchallenge-II

# grey is the new green

Designed and made as part of the second challenge in the IAAC Master in Design for Emergent Futures course "Digital Prototyping for Design", this project is an exploration of the aesthetic and practical possibilities of reusing greywater in an urban environment.

## the idea

Our group ([Ramiro](https://ramiroarga.github.io/MDEF/), [Korbi](https://knr-at-iaac.github.io/MDEF/), and [Cagsun](https://cagsunacemoglu.github.io/MDEF/)) is interested in anthropocene water scarcity and regenerative adaptations to it, such as reducing water usage, reusing water, urban horticulture, etc. 

This project is an assembling of various approaches to these topics, and includes a practical and a more communication-oriented aspects.

It is composed of three main parts:

1) a lipid trap, where greywater can be poured (for example from a bucket used to clean the floor). The trap will seperate lipids and water soluble components

2) a vortex (a turbulent shape made by water due to a magnetic motion powered by a motor). This oxiginates the water, and serves as a visual celebration of the substance

3) a plant filtering tube, where aquatic plants grow and filter out further components of the water

This system is housed in a CNC milled structure. Together, the parts form an initial filtering system which serves as an initial prototype of a component in a larger water management system. It could for example be combined wih a hydroponics setup used to grow things in a domestic environment while showcasing water and its sometimes hidden but central role in our lives (and for life in general).

## what we did

We had already built a basic lipid trap.

![](https://i.imgur.com/n1PCRJv.jpg)


It was build as a laser-cut acrylic plate box, made water-tight using silicone. The box contains separators to guide the water.

The trap works by seperating lipids, solids and the rest of the greywater by density. As the water moves around the seperators leaves the lipids floating on top, the solids sink to the bottom and we are left with 'cleaner' greywater. 

![](https://i.imgur.com/LBvuiuz.jpg)
![](https://i.imgur.com/zWrKCCi.jpg)

For the vortex, we went through a period of brainstorming and making design choices. First, we planned on using a kind of propeller (which we 3D printed in resin), attaching it to the bottom of a container. But we figured it would be a bit difficult to make such a contraption water tight. Also, we wanted to be able to change containers on the fly. So we opted for magnets.

There are a few different ways to build a vortex generator (magnetic stirrer) in this way. We got a bit confused with which polarities should be positioned in which way. This likely depends on what you use as the stirring part. 

Despite a certain lack of theoretical knowledge, we figured out that putting four magnets like this ++ -- (opposite polarities on opposite sides of the axis) on a tube of about 5cm worked well together with a magnetic stick composed of 5 small button-sized magnets. 

The motor we used required around 1.4-1.7 Volt to create the best vortex it seemed to be able to. Interestingly, this did not change that much when we added a larger body of water to be stirred.


## the result

The result we have so far is a not quite functional initial prototype. It features a working lipid trap, and a vortex tube. The very next step will be adding the plant filter. Then, connecting all water containers. Connecting should be relatively easy, having reasonable amounts of water in each at all times may require either manual regulation or some kind of automation. 

![](https://i.imgur.com/gN7179D.jpg)
![](https://i.imgur.com/XJAZXVy.jpg)


## how to replicate the project


### materials

* acrylic plates
* plywood
* tubing
* plastic tube or other suitable container for vortex
* silicone for sealing
* sanding paper and potentially a wood file
* magnets
* motor
* power supply

### process

1) make the lipid trap
    1a) laser cut the acrylic plates according to the file     (see repo) 
    1b) connect the press-fit plates. Seal with silicone       (make less of a mess than we did, if possible..)
    
2) get the vortex to work
    2a) source a motor (...)
    2b) print the magnet holder (see repo). You may need         to adapt the size of the motor and the magnet             connectors according to the materials you have             available.    

3) create the enclosure
    3a) CNC cut the enclosure (see repo)
    3b) sand the pieces
    3c) maybe file the pieces where other pieces need to       fit, depending on your CNC tolerances
    3d) assemble the pieces 
    
4) put everything together (see picture)
