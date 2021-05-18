To actually be able to display anything with three.js, we need three things: scene, camera and renderer, so that we can render the scene with camera.


There are a few different cameras in three.js.
  1) PerspectiveCamera


PerspectiveCamera:
  PerspectiveCamera( fov : Number, aspect : Number, near : Number, far : Number )
  1) Field of View(FOV):
      It is the extent of the scene that is seen on the display at any given moment. The value is in degrees.
      
  2) Aspect Ratio:
      You almost always want to use the width of the element divided by the height, or you'll get the same result as when you play old movies on a widescreen TV - the image looks squished.
  
  3,4) near and far clipping plane:
      What that means, is that objects further away from the camera than the value of far or closer than near won't be rendered.
  
  
  Materials:
    There are 3 different types of materials. Basic, Lambert and Phong.
    ![image](https://user-images.githubusercontent.com/34181215/118680589-80892a00-b81c-11eb-9b65-202025931104.png)
    
    1) Basic:
      This don't need any light source by default.
    2) Lambert:
      In order to see the object we needs a light source by default.
