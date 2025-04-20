---
title: Developing Unibotics' 3D model catalogue
date: 2025-04-12
categories: [3D viewer]
tags: [3d catalogue, google model-viewer, three.js, model assambling, model converting]
---

# Third week on project Unibotics, continuing with the 3D catalogue viewer

This week I continued developed the 3D model catalogue viewer towards a more final prototype. I dealt with automatizing the generation of model cards on the catalogue depending on the available listed models, accesing to them would now load a page on the same window using three.js instead of google's model-viewer since the library gives the web developer more control over the scene. It was also necessary to separete the robot catalogue from the world catalogue due to the number of them which would keep on expanding with the new exercises being added. After designing the new scene's lights and camera I added helpers for the floor plane and different axes so people using 3d model viewers for the first time will have an easier time understanding how ours showcase our models.

At the same time I went on to convert the models currently used on the different exercises to the appropiate new format since both google's model-viewer and three.js work best using glb models. Some of these were separeted in multiple part due to the nature of the model or exercise and required assambling similar to the real robots. Small arrangments were necesarry whether on shapes or textures.

Aside from this I was also finally able to fix the problems I had as an user to run robotics-backend using my GPU while being on Windows 10.