# [Tuto Ryan Laley](https://www.youtube.com/watch?v=4KgIiq6s_yM)


Plugins to activate

![alt text](image.png)

# ZoneGraph

## Create ZoneShape

![alt text](image-1.png)

Change Shape Type to Polygon or Spline

Tag / Empty -> Edit Tags opens Zone Graph settings

![alt text](image-2.png)

Edit Tag 1 for Pedestrian

Lane Profile -> create NPCLane 

![alt text](image-3.png)

![alt text](image-7.png)

Now change Lane Profile from Invalid to 

![alt text](image-6.png)

## Add points to the Line

Hold Alt key and the 3axis

## Data Asset

add Miscellaneous / Data Asset

![alt text](image-8.png)

New Traits 

Assorted Fragments

![alt text](image-9.png)

![alt text](image-10.png)

Agent Capsule Collision Sync

![alt text](image-11.png)

Agent Movement Sync

![alt text](image-12.png)

Agent Orientation Sync

![alt text](image-13.png)

Crowd Member 

Crowd Visualization

![alt text](image-14.png)

![alt text](image-15.png)

Avoidance

![alt text](image-16.png)

Movement

![alt text](image-17.png)

Steering

Zone Graph Navigation

![alt text](image-18.png)

LOD Collector

Navigation Obstacle

Save & close

## NPC Event Graph

Add MassAgent Component

Details / Entity Config with DataAsset_NPC_Config

![alt text](image-19.png)

Compile & Save


## Mass Spawner

add All classes -> Mass Spawner

Details 

Spawn / Count : 10
Entity Type : add the DataAsset

![alt text](image-20.png)

Spawn Data Generators

![alt text](image-21.png)

Menu Build / Build ZoneGraph

## Animated

Go back to data asset. 

Add new trait : StateTree

Choose None -> create new asset StateTree

Save in the folder

Click on Mass Behavior

Double Click on the camembert

![alt text](image-22.png)

Add State : Wander

#### Add new task : ZG Find Wander Target

Select Tags

![alt text](image-23.png)

#### Add new task : ZG Path Follow

Target Location : ZG find Wander

![alt text](image-24.png)

#### Add transition

![alt text](image-25.png)

Compile & Save

