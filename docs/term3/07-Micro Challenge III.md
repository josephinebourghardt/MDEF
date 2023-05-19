---
hide:
    - toc
---
M I C R O ·  C H A L L E N G E  ·  I I I


June Bascaran · Josephine Bourghardt · Sami Piercy 

For the third Microchallenge with the topic of Interfaces we worked with communication methods for the last intervention at the MDEFest that we will be doing in June. For me this was a great opportunity to parctice and learn how to work with Blender and create animations, something that I want to learn more about. Below you can find the process of the Micro Challenge and at the end reflections about the assignment.

C O N C E P T

As part of an experience in June, we will be creating an interactive installation to show the concept of Future Cravings. Future Cravings is a methodology for climate action, using multi-sensory formats to ideate differently around climate issues. It is based on the original problem solving forum: the dinner table (or the fire pit depending on how far back you go) where the dinner experience combines visuals, sounds, storytelling and alternative materials prompting critical conversation.


The installation will be an interactive experience to illustrate visuals, sounds and artefacts within act of conversation and storytelling in a sensory experience to communicate the concept. To further visualise and communicate past and future dinner experiences posters will accompany the installation. To add an extra layer of communication we will create a series of interactive posters, using AR and 3D visuals to show the experience virtually. In doing so we can make our 2D posters engaging and playful. 


P R O C E S S

First, we researched programs to work with AR and animation that could be easily opened with a phone by scanning an image or QR code. We started with A Frame because it is opensource and has webAR applications. 

There was difficulty in placing our 3D model into the code, and we wanted ways to manipulate animation as well. We switched to using Blippar and Meta Spark Studio programs to be able to import our 3D  models and animate them. 

To create the model, we started out by creating a simple model of a dinner table with the tableware that was used in our first dinner. We wanted it to be simple and playful, and not too realistic. The model was built in Rhino, exported to Sketchfab in OBJ format, and imported into Blippar. 



S T E P  · 1 · **T E S T I N G - A R - A P P L I C A T I O N S**

First, we tried using A Frame, and followed code that allowed you to scan from a Hiro image. This worked for the first part of the code which shows a cube in AR, but when trying to import our own 3D models into the code it wouldn't connect and show them. 

![](https://hackmd.io/_uploads/rkL8vcQB2.jpg)

https://aframe.io/
https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf


As we are new to working with AR and animation overall and with limited time constrictions we started looking at other platforms intuitive to beginners. We started experimenting with Blippar. 

Blippar is an online platform where you can build your own augmented reality experiences for the web. It is free, intuitive for beginners and requires no code. 
It has a library of free 3D models, it's free to create, publish and share – with unlimited views.

When using Blippar you need to accept terms and are redirected to Blippars webpage before viewing an image. We had wished to use a platform where images are shown directly when scanning a code, but in this case we still chose to use Blippar due to being user friendly for beginners as we wanted to during this experience practice animation and understand how to use AR.

![](https://hackmd.io/_uploads/r1sLpy4B3.jpg)


https://www.blippar.com/


S T E P  · 2 · **3 D - M O D E L**

The 3D model we used was created in Rhino - a dinner table with tableware in different forms to in this case illustrate how a dinner setting could look at a Future Cravings concept dinner, here with the topic of the sea. The file is exported as an OBJ which can be imported to Blender for animations as well as uploaded to SketchFab to be used directly in Blippar.

This is the 3D model animated directly in Blippar, which we uploaded to SketchFab. We were able to play around with creating a background scene, lighting, and directional movements. We then did a version of the table animated in blender. 

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjSpt4ug0&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

This can be tested out here with the QR code:

![](https://hackmd.io/_uploads/r1ePklNrh.jpg)



S T E P  · 3 · **A N I M A T I O N - I N - B L E N D E R**

The goal is to create an interaction with a 2D poster that plays with forms and shapes of the tableware that are shown in a poster. Meanwhile we also wanted to learn and practice using Blender for animation where this was a great opportunity to do this. 

After importing the 3D file in OBJ format into Blender this tutorial (https://www.youtube.com/watch?v=CBJp82tlR3M) was followed to learn the basics of animation and to move objects in a scene. 

Different actions of rotation, location and scale were added to the different objects on the table. 

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjSB5Y0CE&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a 

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjSIf2ivM&#x2F;watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a 


S T E P  · 4 · **B L E N D E R - T O - B L I P P A R**

   
   
The animation is then rendered into a video that can be uploaded directly to Blippar.
   

To make an AR video in Blippar you create a profile, start a project, choose a qr code image, where you can choose your own or let Blippar generate one for you. When in your new project you press the plus button to upload a file and choose your video file. Drag it to the scene and scale it to desired size. 
   
   
   ![](https://hackmd.io/_uploads/B1yRXnQS3.png)


   
To preview press Preview Project at the top right where you will be prompted to go through the steps of scanning the codes before seeing the project in AR. 
![](https://hackmd.io/_uploads/S1uh3qmBh.jpg)

When happy with how it looks publish the project. The QR codes can then be placed where you want people to interact with them to view the AR experience directly with their phones. 
   
   
   
![](https://hackmd.io/_uploads/Sypv9pQS2.png)

  
   

Example posters - This can be used on printed posters. With the QR code to access Blippars webpage and the AR code as an image. The animation starts as the image making it move when looking at it through your phone.
   


<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjSJOo8Ns&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>




S T E P · 5 · **A N I M A T I O N  - I N -  M E T A S P A R K S - S T U D I O**


Meta Spark Studio is a software platform designed for the creation and development of immersive virtual reality (VR) and augmented reality (AR) experiences. It is intuitive and user-friendly program that offers a wide range of tutorials for learning purposes. Also, it offers a variety of tools and features that helps to easily create what you have in mind. 
   
By following some tutorials on how to use the program en ended creating cool animations en AR by using image tracker. Initially, with objects, after with 3D Model Tableware. 

After creating the animation, was able to create an instagram filter. This can be seen here:
https://www.instagram.com/ar/259930709740588/?ch=NDhmZTNkNWE2NTJiODE2MmRiMjk2OTZlNDg1YTI0YmI%3D
   
<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjRMTUMXw&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a 

Other explorations:
   
<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjSqky0vY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


##  F U R T H E R - E X P L O R A T I O N S

The next step would be to make the table or moving objects be directly imported into AR. This way we can have free floating animated objects. Below the plant was built in Blender and coral was imported from SketchFab. Both were animated in blender and were able to be directly imported into Blippar as a .glb file. Only the scaling was able to be transferred, but not the rest of the animation. 

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjTSCEKtE&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFjTpcKreY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

Coral SketchFab:
https://sketchfab.com/3d-models/coral-c26e47859f0945d69a4e2944ee80b995

Tutorial for plant:
https://www.youtube.com/watch?v=Z1QG1FOvPk8&ab_channel=PolygonRunway

Find the full documentation here: 


R E F L E C T I O N S 

To make the most out of this challenge working with interfaces we chose to work on things we wanted to learn more about and that can add to our project. I want to learn to use Blender for animations and used this challenge to parctice this. I have used different CAD programs before and work well in Rhino, yet it still took longer time than expected to find commands and tools in Blender. It was fun and quite simple to make basic animations that could work for our project and communicating it. I struggled with the small details of rendering and figuring out how the program works. Realistically I know how time sonsuming it is to learn a new program, but it's still amusing the amount of time spent on getting stuck on basic prompts before learning where they are in a new program. Im greatful we as a group decided to use the AR program Blippar instead of also having to code in A Frame to make AR animations, now we at least got the chance to produce simple things and get to know how Blender, animation and AR with Blippar without too many frustrations. This resulted in for me at least, that I want to continue and refine what we did during the two and a half days that a Microchallenge is, and keep working on making it better for the MDEFest. As well as learn more animation in Blender, where using it for two days helps a lot to find your way in the program and how its built.