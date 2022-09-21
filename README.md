
## Project Description

The aim of the project was to study the creation of complex materials and a system for building a landscape. The project only uses Blueprint. Version Unreal Engine 4.26

The projects use assets from Megascan and the Epic Store.

Water shaders, water effect decals (moisture and caustics) and terrain surface shaders are a standalone work.
The main logic of their work is in the screenshots below.

## Cinematic 

Short demonstration of the result

https://user-images.githubusercontent.com/80645926/191496944-9a71d2d6-9b66-4d55-a2b6-6f3b25d762fe.mp4

## Materials

### Water material and decals

 - **Water material**

![Water material](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20.png)

 - **Water Flow Maps**
 
To create an interesting pattern of water flow behavior, a third-party software product FLOWMAP PAINTER was used
[FLOWMAP PAINTER](https://teckartist.com/?page_id=107)
 
![Water Flow Maps](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(3).png)

 - **Water Flow Maps Function**

![Water Flow Maps Function](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(2).png)

 - **Decals. Water caustics and moisture effect**
 
 ![Water caustics](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(5).png)
 ![moisture effect](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(4).png)

 - **Water material instance**
 
The water material has settings.
As a result of a water material instance, you can adjust the physical characteristics of water behavior (flow rate, wave size, wave intensity, foam intensity, color of water that is closer to the bottom or surface).
 
 ![Water material instance](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-21.png)


### Landscape material

 - **Landsacpe material**
 
 ![Landsacpe material](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(6).png)

 ![Landsacpe material1](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(7).png)
 
 ![Landsacpe material1](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(10).png)

 - **Packing and unpacking landscape texture**

To create terrain textures to reduce performance overhead. Card packaging was used (AO, Albedo, Cavity, Displacement, Rougness, Normal) Substance Designer was used for this. Next comes unpacking inside UE

Packing landscape texture in Substance Designer

 ![Packing](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(9).png)

Unpacking landscape texture in UE

 ![Unpacking](https://github.com/Kirill-Geskin/IMG/blob/main/2022-09-20%20(8).png)
