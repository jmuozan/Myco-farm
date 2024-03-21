# Myco-farm
## Microchallenge I
**Project by:
[Everardo Castro Torres](https://everardocastro.github.io/mdef1/)
[Jorge Muñoz Zanón](https://jmuozan.github.io/mdef-website/)**

The following project tries to put to the test a new way of manufacturing. Based on the growth of mycelium, this project offers a different approach to grow mycelium than doing it in a Lab.

By planting molds to the soil connected via 3d printed clay structures that allow mycelium to both, grow through the mold and expand its net to eventually connect to the mycorrhizae. This method, allows exchange of nutrients between the mold and the natural ecosystem. Through this artifact we explore the idea of taking resources in a more responsible way, exchanging nutrients and the new mycorrhizae network for a desired object, fruit, etc...
Further research is needed in order to not alter the ecosystem's balance (fungi species, plant species).
![](./IMGS/Concept_references/sketch 1.jpeg)
![](./IMGS/Concept_references/sketch 2.jpeg)

The myco-farm takes the main idea and converts it into an ant farm allowing us to be observers in the evolution of growth of the mycelium. The myco-farm, consists of an acrylic box with the 3d printed connections and mold sectioned and fixed to the acrylic wall so we can see the whole process of growth.



## References 

https://aleawork.com/back-to-dirt-mycelium

https://www.boisbuchet.org/workshop/mycelium-nothing-really-matters/#

## Integrated Design

To test the initial hypotesis we decided to make a small sample that we could observe and analyze the growth and connections of the mycelium without taking a lot of time. To do it we decided, similarly to an ant farm to make a section of the mold and connection and the ground. The artifact consists of a surrounding made out of an acrylic box, half mold and half the connection piece connected between each other and to the acrylic wall. The box will be filled with the mycelium and soil so we will be able to properly observe the evolution of the growth. Also, the box will have lateral space to add sensors or other living beens so we could also see how the mycorrhizae interacts with them.

![](./IMGS/3D_Renders/Myco-Farm.46.png)

## System Diagram

As it was explained before this is the way the concept design was imagined before fabrication:
![](./IMGS/3D_Renders/Exploded.png)

- **1, 2, 3, 4 Box:** Acrylic box that will make "imaginary" surroundings for us to see through them.

- **5 Connection module:** This piece, as it's name sais will be the ***connection*** between the mold and the soil. It's a semi circular tube able to fit the top part on the mold and full of holes on the side so the mycelium network will be able to expand.

- **6 Mold:** The last piece it's the mold itself, it's cutted by half and it has to be connected to the face of the box, on the bottom it has a semicricular hole where piece 2 will be connected. Also, has different breathing 


## Piece Definition and Fabrication Process

- Box: For the fabrication of the box, we designed the 2D shapes of the different faces on Rhinoceros, applying the different finger edge joints on the sides and creating new squared connections on the front face to join the box with both the tubular connection and with the mold.After this, we assigned different colors following the hierarchy of the laser cut machine, red for the interior cuts and blue for the outside cuts.



- Connection: To manufacture this piece we tried two different fabrication techniques. First we tried with the hacked 3D paste printer because we wanted the final result to be printed in clay so the hole artifact will be and feel more natural but the machine gave us a lot of problems while printing. For that reason, as we didn't have a lot of time and the goal of the challenge was mainly to test the initial hypothesis, we ended up deciding to print it in PLA as the mold. 
As it was mentioned before, the piece contains different squared extrusions on the front face so it can fit with the holes made in the box front face, Also, on the bak part we added different hoes so the mycorrhizae can expand it's network through the soil.

![](./IMGS/3D_print/IMG_3253.JPG)
![link text](./IMGS/3D_print/IMG_5966.jpg)

- Mold: To make the half/mold we decided to print it with PLA too. The semi circular hole on the bottom part is made so the roots of the mycorrhizae can travel trough and fill both the mold and the connection piece. On the back part, we added some holes so the mycelium inside will be able to breath. In the folder, make a mold, you will be able to create your desired shape inside the mold as we facilitated open 3D NURBS based file formats (.igs and .step) with the mold shape filled. By making a simple ***boolean difference*** operation in your desired 3D software you can print the desired shape inside the mold to fiti it in the ***myco-farm***

![](./IMGS/Laser_Cut/IMG_5973.jpg)

## Mycelium


1. Prepare the substrate. In this case, small amount of coffee was added for additional nutrients.

![](./IMGS/Mycelium/1.jpg)

2. Place the substrate in a heat resistent bag to sterilize it in the pressure cook.

![](./IMGS/Mycelium/3.jpg)

3. Put the pressure cook in Meat mode (fablab biolab) for 45 min.

![](./IMGS/Mycelium/4.jpg)

4. Sterilize EVERYTHING else with alcohol and use gloves.

![](./IMGS/Mycelium/5.jpg)

5. Put on a flame to create a sterilizing bubble where you can work in.

![](./IMGS/Mycelium/6.jpg)

6. Place a layer of dirt to support the conection piece.

![](./IMGS/Mycelium/8.jpg)

7. Take the subsrate out of the pressure cook and add sculpting nutritional mix.

![](./IMGS/Mycelium/9.jpg)

8. Add straw innoculated with mycelium and mix.

![](./IMGS/Mycelium/10.jpg)

9. Add the mix into the connection and mold.

![](./IMGS/Mycelium/11.jpg)

10. Fill with dirt and place a little plant, in this case it was a celery <3.

![](./IMGS/Mycelium/11.jpg)



## Data Capture Implementation

To properly observe and analyze, we decided to add some sensors to the box, measuring temperature, humidity... As we were suggested to use the ***Parrot Flower-Power*** sensor, an all in one sensor capable of measuring temperature, light, fertilizers and watering. As it was an all in one sensor with a dedicated phone app, we thought it will be easier than assembling and coding all by ourselves. Problem came when we realized the sensor is no longer supported by Parrot so we had to ***hack*** it and extract the data with a computer and save it in a .csv file for proper analysis later. This was a hard process where we needed a lot of help from Mikel to read data from the sensor with a Raspberry. As we didn't had enough time and we lack some technical skills we didn't finish this part yet. For future iterations will be ideal to manage to take that data and put it in a csv file for visualization.

## Final Reflections

![](./IMGS/Final/Final.jpeg)

