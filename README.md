# 3D_citymodels
Use Git large file storage (https://git-lfs.github.com/) before cloning this repo. This repo contains the work files blend of the buildings in virtual Oulu. 

In this repo each building is its own object. Each building is on its designated area (map.jpg), 
but the buildings area named based on the address they are on on the south-north streets e.g Isokatu, Kirkkokatu... 
(Streets that go west-east are not used in naming the files apart from textures). All textures required for a speific 
building can be found from subfolder /textures. Some building may contain more than ten material files, the reason 
for this repo in part is to have a version control for joining the materials and atlassing/updating the textures, to make it easier to export these models and create big scenes in Unity, UE4, Meshmoon etc. 

The street meshes are named according to the areas (map.jpg). Streets have elevation that corresponds 
to the elevation of the real citystreets of Oulu, but the meshes are joined, so that they can be used for terrain, although it is recommended that you to do your own simple physics constraints for the terrain and building walls as some of the models  have quite high polygon count. 
(Minimum area for streets in this repo is four blocks, the focal point is always on the crossroads.) The original street meshes 
surrounding the blocks can be found from: 
https://oulu3d.svn.beanstalkapp.com/oulu3dinfra_ydin/ 

Map describing the areas:

![alt tag](https://github.com/Plij/3D_citymodels/blob/master/areas_map-3.jpg)

