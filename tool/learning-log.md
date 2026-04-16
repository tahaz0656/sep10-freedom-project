# Tool Learning Log

## Tool: *Aframe*

---

### 3/16/26:
* Watched this whole video about [Image Textures and Materials](https://www.youtube.com/watch?v=XUwvKXPlnJY&list=PL8MkBHej75fJD-HveDzm4xKrciC5VfYuV&index=7)
* The video shows how to adjust different material properties such as color, opacity, and roughness to create various visual effects.
* The tutorial walks through using the  ```<a-image> ```tag to display images as textures on surfaces in a virtual scene.
* You can apply textures to geometric shapes (like boxes or spheres) using the src attribute in A-Frame components. For example ``` <a-scene>
  <a-sphere position="3 1 -5" src="url(image.jpg)" radius="2"></a-sphere>
</a-scene> ```. This shows how to apply texture to a sphere, the "a-sphere" element creates a 3d shape, the "src="url(image.jpg)" applies the texture ot the sphere, and the "radius" defines the size of the sphere.


### 3/23/26:
*


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
### 3/30/26



### 4/15/26
Building a robot that picks up garbage automatically
* Day 1 :
I will focus on building the frame, I will use a large and flat <a-box> as the main platform to hold all the components. Then attach 4 cylinder (<a-cylinder>) shapes and then rotate them to face outwards like tires for example. Move the wheels to corners and then position them.
* Day 2 :
Place a tall (a-box) on the back half of the chassis ( which I learned was like a skateborad deck of the robot, it's job is basically like holding wheels at the bottom and like the garbage bin ). Put 2 small <a-sphere> shapes on the front because it could help make it look like a fake person.
* Day 3 : Build the main arm using a long thin <a-box> poniting forwards from the chassis. Add claws to the arms <a-box> pieces and try to angle to make it look like grippers to pick up garbage and then the coloring.
