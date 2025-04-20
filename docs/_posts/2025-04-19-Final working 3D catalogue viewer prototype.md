---
title: Final working 3D catalogue viewer prototype
date: 2025-04-19
categories: [3D viewer]
tags: [3d catalogue, google model-viewer, three.js, postgre database, http requests]
---

# Fourth week on project Unibotics, finishing the first final 3D viewer protype

Due to the easter holidays this work week was a bit shorter. I was still focused on finishing the 3D catalogue so after the rest of the team and I were finally satisfied with the viewers and scenes themselves and how they were working to allow the users to observe the models, it was time to polish the final look and move the models to the backend's infrastructure instead of the local folder they were located in so far.

This implied both designing the svg icons for the new apps and adding the viewer models to the database, which at their own turn would also now need to be retrieved through the information the database contains through a proper request.