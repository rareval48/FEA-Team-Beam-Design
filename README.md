# FEA-Team-Beam-Design

## Table of Contents

* [FEA_Part 1](#FEA_Part_1)
* [FEA_Part 2](#FEA_Part_2)
* [FEA_Part 3](#FEA_Part_3)
* [Extra Design](#Extra_Design)


## FEA_Part_1
### Description
Initial design of the beam

### Part Image
<img src="https://user-images.githubusercontent.com/71342195/201368972-60be90cd-ab27-4af6-bca0-1178c419fffb.png" width="600"><img src="https://user-images.githubusercontent.com/71342195/201956934-0a3b6bb5-5690-4185-a896-5e9d26e0884a.png" width="200">

### Reflection
Our initial design is based on an I beam. But instead of making an I beam we used triangles so that there was more support and rigidity. But since we needed to get rid of weight we needed to cut holes into the sides so that the total beam weight is >= 13 grams. We did pretty good on our first idea considering that we also got rid of alot of weight by getting rid of extra hangovers that wouldnt've didnt give as much support as it should've considering all the weight it was.

## FEA_Part_2
### Description
Simscale Workflow

### Part Image
<img src="https://user-images.githubusercontent.com/71342195/201369246-3574bfac-4779-4b21-ba10-79b7a163ae12.png" width="600">

### Reflection
We did decent on our first attempt but made alot of changes. We ended up making changes to the beam so that there was more support on weak points and less support on strong points. As we added more support there was also weight that was added. So we took cut more triangles in places that didnt need support and took of 2 support walls to cut weight. Once we got down to an acceptable weight we then retested the beam.

## FEA_Part_3
### Description
Iterative Design

### Part Image
<img src="https://user-images.githubusercontent.com/71342195/202476218-bf3bfc9b-608c-4a95-8528-45043f271c07.png" width="600"><img src="https://user-images.githubusercontent.com/71342195/201960051-f495fbc2-ce61-4e19-ba86-23a775671d54.png" width="200">

### Reflection
As you can see we added more triangles to take stress off of weak points and we ended up adding more support in the center of the beam. We decided to get rid of a diamond in the pattern on the side wall and add a triangle and a smaller diamond to reduce stress. When we retested it we got a better score on this beam compared to the first beam.   

## Extra_Design

### Description
Failed extra design

### Part Image
<img src="https://user-images.githubusercontent.com/71342195/202484399-a602cb3b-7bca-48d5-a615-8cb30eb71620.png" width="600">

### Reflection
In what we thought would be a fix for our final design, we added beams in the middle of all the triangles. This was to counteract the stress which was conectrated at the top of these triangles. When we ran the simulation for this design, the Von Mises stress was higher, which was weird. Also the stress point was in a place that didn't make sense. In the end we ended up not going with this design for these reasons. 



