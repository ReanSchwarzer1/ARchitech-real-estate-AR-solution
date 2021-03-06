<!DOCTYPE html>
<html>
<body>
<h1 align="center"> ARchitech-real-estate-AR-solution </h1> 


<h2 align="center"> This project was made in purpose for the Open AR problem statement for the ACM Hacksprint 2.0 hackathon. </h2>  


<h2 align="center"> The Problem Statement </h2>  
On the onset of the pandemic, a number of fields that prioritized, nay mandated, physical interaction with customers such as the construction and real-estate industry, are crumbling do to the lack thereof. 

It has become a necessity for such work cultures to embrace the world of the virtual and implement strategies that not only tackle the "customer's physical presence is a must" mindset of such industries, but further buttress the previously elucidated advantages of working "virtually".

<h2 align="center"> Idea / Approach </h2>  
To combat such a situation, we have devised an infrastructure platform that has the capacity to support a number of occupations that rely on a more 'hands-on' work ethic.

Using cutting edge Augmented Reality technology powered by AR Cloud Service Echo AR, which allows for the placement and view of real-estate in real-time, the application allows for the collaboration of all fields within the ‘infrastructure’ realm to provide a succinct view of multiple renditions of the house, including the finished, unfinished and an under construction view.
<h2 align="center"> Tech Stack </h2>  
<li>Echo AR<br></li>
<li>Unity Engine<br></li>
<li>Blender<br></li>
<li>Unity Engine<br></li>
<li>Android (v7 and above) Device with ARCore support<br></li>

<h2 align="center"> Application of Augmented Reality </h2>  

<li>A real-time Augmented Reality application which renders multiple infrastructural models in worldspace through Android Devices with an ARCore enabled Camera.<br></li> 
<li>AR modules include 1:1 scale interactable and explorable models. These modules can be selected manually by the user through the UI menu.
The modules consist of:<br></li>
Furnished 1:1 scale model of a House with a UI overlay
Empty 1:1 scale model of a House with a UI overlay
1:1 scale model of a House with structural details such as layout and sizes.

<li>Additional echoARbuddy app includes Construction Phases expressed through 3D models created in Blender and rendered through the echoAR console<br></li>

<h2 align="center"> Day 2 Additions for the Hackathon </h2>  

<p align="center">
<img src="https://github.com/tamizhis5n/ARchitech-real-estate-AR-solution/blob/master/Images/day2add.PNG?raw=true">
</p>

<p align="center">
<img src="https://github.com/tamizhis5n/ARchitech-real-estate-AR-solution/blob/master/Images/day2ui.PNG?raw=true">
</p>

<h2 align="center"> Day 3 additions </h2>  
<li>We started out with an aim to create an immersive AR experience. Our initial project idea was an AR Portal which would present the user with a real-time render of the interior of the models.<br></li> 
Problems faced:<br>
We realized this solution doesn’t accurately represent a real-estate demonstration.<br>
We faced problems with multiple mask renders.<br>

<li>Started coding the solution and modelling the preview models on C4D only to face export issues, therefore changing our tool to Blender.
We acquired new skills such as:<br></li> 
Animating UI in Unity and quick scene transitions for better UX<br>
Advanced modelling and texture baking in Blender<br>
EchoAR SDK and seamless implementation<br>
Model runtime implementation in Unity using Echo AR SDK<br>
ARCore Cloud Anchors (GPS Trackers)<br>

<li>Upon consulting with Mentor who suggested we increase the scope of our solution we added new and improved functionalities such as:<br></li> 
Easy addition of Custom models using EchoAR console<br>
Addition of EchoAR APIs in the client side application<br>
Construction phase previews<br>

<li>Finally we reviewed our code, prototyped our application and committed the changes to our github repository.<br></li> 

<h2 align="center"> Working Demo </h2>  

For the full video visit: https://drive.google.com/file/d/1Vme4T5QHkhvyDRu-nrMR0awDXzoXvMdG/view

![Demo1](https://github.com/tamizhis5n/ARchitech-real-estate-AR-solution/blob/master/Images/demo1.gif "Demo1")
![Demo2](https://github.com/tamizhis5n/ARchitech-real-estate-AR-solution/blob/master/Images/demo2.gif "Demo2")


<h2 align="center"> Instructions </h2>  

Download and install ARCHitechDemo.apk and run on an ARCore supported android device.

</body>
</html>



