# Hack Technology / Project Attempted
- VR, Building a Museum with Unity3D
- AR, Mobile Applications using Unity

## What you built?

We built a VR Museum from scratch using Unity3D.  

<img width="1440" alt="Screen Shot 2022-09-30 at 2 53 59 PM" src="https://user-images.githubusercontent.com/72226780/193338217-204adf27-3fa2-4aa3-99d2-0d00e4cbbfb2.png">

<img width="1426" alt="Screen Shot 2022-09-30 at 2 53 42 PM" src="https://user-images.githubusercontent.com/72226780/193338809-1f14dbbe-e90b-4dc5-b255-034ecf5b7217.png">

<img width="1440" alt="Screen Shot 2022-09-30 at 2 54 46 PM" src="https://user-images.githubusercontent.com/72226780/193338156-f361ac17-4f5b-40dd-a2b8-e81edd0b3174.png">

<img width="370" alt="Screen Shot 2022-09-30 at 2 55 03 PM" src="https://user-images.githubusercontent.com/72226780/193338175-ebc1d5ea-7bf8-4bc2-b147-0fc7ad8dcc63.png">

## Who Did What?

Melissa and Will pair programmed both projects. Melissa generally focused on the VR Museum, while Will dove into the AR Mobile Applications. We both followed the tutorials alongside one another, ensuring we downloaded the necessary software and dependencies in case we ran into any individual issues and thus would be able to pick up on either one's work space. William ran into hardware issues with Unity causing his computer to overheat, resulting in pair programing and implementing the Unity projects primarily on Melissa's computer. I will also note the educational aspect of the AR course took much of our time to prepare for the Unity interactions. 

## What you learned

The Museum VR Tutorial was a great introduction to working with Unity 3D and creating a virtual reality space. We initially began with creating a confined space using the Unity Cube 3D object. This required manipulating the object's position to align with what would become the walls, and roof of the museum. We used a wood-resembling material to alter the museum floor which was a Unity plane. It was interesting to learn how to use these built-in objects and apply materials to enhance how realistic they appear. 

Once having our general space set up, we applied area lighting to further convey a realistic setting through an indoor light application. We used an area light object specifically a baked light to fit the size of our museum. When we applied the light, we had to ensure that the walls, floor, and roof were properly placed to avoid any unexpected shadows from the exterior surroundings. 

Now having a realistic setting to work with, we began adding our museum displays and artifacts. We began with placing one cube object and extending its length to resemble a column. We then placed the artifact on the column, scaling it to a reasonable size and placing it directly on top of the column. It was particularly difficult to work with these objects without a mouse, given that the Unity movements and scalabilities work best with a mouse's functionalities as opposed to a touch pad.  

We added descriptions to complement the museums displays. It was interesting working with text and scaling it to a fixed place on the wall. Again, it would have been helpful to have a mouse that facilitated the movements. To continue enhancing the virtual museum experience, we added audio to the display which read the description that was provided. We used the canvas and button objects to create an interactive button for the user and applied the audio within this scope with a C# script. 

To expand the museum experience, we added two more artifacts and followed the steps above, ensuring there was consistency in our virtual reality space. We noted how important it was to apply global illumination to our objects, mainly the columns, to create a seamless scene with the area lighting. We also learned about altering resolutions and its effect on the appearance of the virtual space. 

We were unable to complete testing on our VR Museum as we do not have access to an Oculus, however our virtual space does appear as expected. 

When trying the AR marker recognition, it was not too difficult to install the software; however, finding a marker that was accepted by Vuforia was extremely challenging. When using the online marker generators, it would not be the correct sizing. Once finding something that was accepted after using online forums to find an acceptable marker. There was additional issues on readability of the marker only scoring a 3/5 causing issues down the line. Ultimately hardware issues with William's laptop caused us to shift towards the VR project described above. 

We will note that the tutorial also covered an overview of AR, and gave us the general understanding of the various types of XR. The marker one seemed the most reasonable to implement; however, since neither of the team members have an android, it made testing an issue. 

## Authors

- Melissa Valencia
- William Perez

## Acknowledgments

- Museum VR Tutorial: https://www.youtube.com/watch?v=7dwfOg9v3Zg
- AR Mobile Applications: https://www.youtube.com/watch?v=WzfDo2Wpxks
