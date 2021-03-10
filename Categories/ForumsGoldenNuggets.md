# Forums' Golden Nuggets

* [**Efficient AABB/triangle intersection in C#**](https://stackoverflow.com/a/17503268)  
**Original Question**
  > Can anyone recommend an efficient port to CSharp of any of the public AABB/triangle intersection algorithms.
  >
  > I've been looking at Moller's approach, described abstractly here, and if I were to port it, I would probably start from this C++ version. This C++ library by Mike Vandelay seems like it could also be a great starting point.
  >
  > ...or... any other "wheel" that can take a triangle of Vector3's and tell me if it intersects with an AABB), relatively efficiently.
  >
  > There seem to be a variety of algorithms, but most seem to be written in c++, or just described abstractly in white papers and I need a c# specific implementation for our application. Efficiency is not key, but c# is. (though efficiency is obviously nice too of course ;p )
  >
  > Any C# options, before I wade through a "math" port ;) would be greatly appreciated! Thanks.  
  
 ---
 
* [**Get a specific bit from byte**](https://stackoverflow.com/a/4854257)  
**Original Question**  
  > I have a byte, specifically one byte from a byte array which came in via UDP sent from another device. This byte stores the on/off state of 8 relays in the device.
  >
  > How do I get the value of a specific bit in said byte? Ideally an extension method would look the most elegant and returning a bool would make the most sense to me.

---
* [**How to compare two shapes?**](https://stackoverflow.com/a/22166032)  
**Original Question** 
  > Is there a way to compare two geometric shapes (or any two more generic data structures), without using the brute force when a tolerance is involved?
  > 
  > The brute force (that is comparing each value of each object against each value of the other object) works but it's slow, and I can't use it.
  > 
  > I tried sorting the data and comparing two sorted collections. It's fast, but it only works with zero tolerance. As soon as I add the tolerance I get lost. The problem is that two values can be identical when I compare and different when I sort.

---
* [**Is generating a .PTX file a must?**](https://forums.developer.nvidia.com/t/is-generating-ptx-file-a-must/82662/4)  
**Original Question**  
  > Is there a way to prevent the app from generating external .ptx file and integrate it into .exe itself, somehow?
  >
  > For example:
  > 
  > I have my .exe and 3 dlls (glad, glfw3, sutil_7_sdk) from optix sdk samples and I’d like the .exe without the need to have the .ptx file with it. Is it possible?  
  >
---

* [**Mod of negative number is melting my brain**](https://stackoverflow.com/a/6400477)  
**Original Question**  
  > I'm trying to mod an integer to get an array position so that it will loop round.
  > Doing `i % arrayLength` works fine for positive numbers but for negative numbers it all goes wrong

