# Hi, I'm Kutay

I work in two areas. On the data side, I like projects where math meets finance. On the graphics side, I build real-time 3D scenes in Unity, model and draw my own assets, and write my own shaders.

## What I use

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat)
![LightGBM](https://img.shields.io/badge/LightGBM-2E8B57?style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![HLSL](https://img.shields.io/badge/HLSL-5C2D91?style=flat)
![Shader Graph](https://img.shields.io/badge/Shader_Graph-333333?style=flat)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat&logo=blender&logoColor=white)
![Aseprite](https://img.shields.io/badge/Aseprite-7D929E?style=flat)

## Real-time 3D rendering

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://github.com/user-attachments/assets/5f0a4a17-1dce-449e-960d-2dc6e0a15803" width="100%" alt="Nature scene at sunset" />
    </td>
    <td width="50%" align="center">
      <img src="https://github.com/user-attachments/assets/c12cc537-1fc1-4895-86ff-b3b267b17d64" width="100%" alt="Real-time 3D scene" />
    </td>
  </tr>
</table>

Most of my Unity work is small scenes built around one rendering technique, with custom shaders and hand-made assets:

- **Foliage and terrain.** Toon-shaded grass and trees modeled in Blender and scattered across sculpted terrain. [Code](https://github.com/kutpac/shader-demo-env) and [itch.io build](https://kutpac.itch.io/nature-shader-demo).
- **Ocean simulation.** A spectrum-based ocean simulated in a compute shader, with several wave cascades, foam, subsurface scattering and specular highlights.
- **Water shading.** A Shader Graph water shader, reused in a couple of my scenes.
- **Wave animation.** HLSL wave and swash functions for a beach, driving both vertex displacement and gameplay height lookups.
- **Post-processing.** Full-screen dither and posterize effects built in Shader Graph.

## Games and gameplay prototypes

**[zombie-shooter-demo](https://github.com/kutpac/zombie-shooter-demo)**
An isometric survival shooter with a PS1-inspired look. Zombies notice and chase you, the horde grows the longer you last, and the weather changes as you play. [Play it on itch.io](https://kutpac.itch.io/isometric-zombie-shooter-demo).

**Car prototype**
A stylized coastal driving scene. The car uses a custom raycast suspension model, and the world has a shoreline, toon water, palm trees, road signs and a pixel-art look. Props were modeled in Blender and textures drawn in Aseprite.

**First-person movement prototype**
A fast first-person controller built as a state machine, with dash, slide, wall run and ledge climb, plus katana combat with hand-modeled viewmodel arms.

## Data and machine learning

**[lendingclub-credit-risk-ml](https://github.com/kutpac/lendingclub-credit-risk-ml)**
Loan default prediction on LendingClub data, comparing logistic regression, random forest, XGBoost and LightGBM. Includes feature engineering with leakage prevention and threshold tuning.

**[particle-filter-object-tracking](https://github.com/kutpac/particle-filter-object-tracking)**
Benchmarks several metaheuristic optimizers (PSO, Firefly, Slime Mould, Grey Wolf and others) combined with particle filters for tracking objects in video.

## Find me

[LinkedIn](https://www.linkedin.com/in/kutpac) · [itch.io](https://kutpac.itch.io)

