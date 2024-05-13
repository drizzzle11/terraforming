Terraforming is a computational design workflow written to procedurally develop different landscapes based user-inputs (curves for roads and rivers/creeks and meshes for buildings). 
Varying input curves and building locations generate different landscapes. The algorithms have been written using C# script in the Grasshopper environment. 

The following components have been developed for this workflow: 
create_land : creates meshes for land, river, plantable  land, barren land and roads; 
plants_partition: segregates meshes which are  more plantable and less plantable based on the amount of sunlight received; 
trees: populates trees on more plantable meshes
shrubs: populates shrubs on less plantable meshes
