# Lost Chicken's Food :chicken:
#### Gabriel Esteban Castillo Ramirez
#### Based on Alejandro Paolo Daza's Game : "La llorona".
### Introduction
The Chicken is lost in the Highway and its food is spread all over it, the Chicken is hungry
and needs to eat the corn even with cars going at high speed.

### Game instructions
* The chicken is controlled with the keyboard's arrows or with the keys W A S D, the objective of the game
  is to collect all the corn possible, the more corn the chicken eats, the more points the player gains. 
* The obstacles are the vehicles in the screen, they can go fast or slow, if the chicken gets touched by 
  a vehicle, the game will end.

<img src="https://user-images.githubusercontent.com/43209755/60149719-4b444080-979b-11e9-981c-fa76689d7db6.png" width="560">

### Game Structure
The Game uses different languages :
* For the visual aspect HTML and CSS is used.
* For the logical aspect JavaScript is used. 

#### Main Structure
The principal structure is located in the file "script.js", we will see different aspects as:
1. The continuity leans on two states, when the Chicken is alive and when it doesn't.
2. Entities such as the Chicken, the Corn and the Cars are treated as Objects.
3. The logic given to capture the keys lays on this script as well.
4. Events of interaction as colliders given in the main function (run()), also the control of the states mentioned before.
5. The deployment of instructions and reseting the game. 

#### Visualization and its interaction 
The only file "index.html" with the backup of "default.css" create the visual base of the game, in these files we find:
1. The visual deployment of the game ("index.html").
2. Information of the creator and collaborator and a brief description of the game. 
3. The auditive deployment of the game (All the audios are referenced, these are at the end of this text). 

#### Functionality
The files that set the individual properties of each entity are located in "gallina.js","maiz.js" and "carro,js". 
Each one of the scripts define the base of visual change and individual logic. 

Beginning with the chicken, it has these attributes:
* Position in "x" and "y".
* Images (sprites).
* Alive/Dead state.
* Score.

In addition, it has these behaviours:
* Refresh the position while the user presses the movement keys.
* Drawing itself in the enviroment together with the score.
* Modifying characeristics when a collision is given.


Continuing with the corn, it contains more simple functions and attributes, which are:
* Position in "x" and "y".
* Image (sprite).
* Eaten/Not eaten state.

Being complemented by its functions:
* Drawing itself in the enviroment.
* Changing positions whenever it gets eaten by the chicken.


And ending with the cars, which contain different behaviours and complementary variables, these are:
* Position in "x" and "y".
* Images (sprites, one for each car).
* Velocity.

At last, we will see the different functions contained:
* Initialize the image and velocity of the car.
* Reset the characteristic whenever a car gets to the edge of the enviroment.
* Drawing itself in the enviroment.
* Refresh the position depending on the velocity.

### Execution
By clicking the link below the game will automatically start:
[Lost Chickens Food](
https://gabelonio.github.io/Lost-Chickens-Food/)

### Miscellaneous

1. Corn Image : "Minecraft: Pocket Edition Item Crop Wheat" Available at: https://www.uihere.com/free-cliparts/minecraft-pocket-edition-item-crop-wheat-minecraft-pixel-art-doge-5141279

2. Cars Image: "Cute vehicles by toribird" Available at: http://pixeljoint.com/pixelart/81033.htm

3. Highway Image: "Toon road texture by davidstenfors" Available at: https://www.davidstenfors.com/#!/downloads

4. Background Image: "powerpuff girls house - Google Search" Available at: https://co.pinterest.com/pin/390757705152412055/?lp=true

5. Tombstone Image: "Pinsanity 8-Bit Pixel Tombstone"Game Over" Enamel Lapel Pin" Available at: https://www.amazon.com/Pinsanity-8-Bit-Pixel-Tombstone-Enamel/dp/B07BCMXZKP?language=en_US

6. Chicken Image: "whtdragon's animals and running horses- now with more dragons!" Available at: https://forums.rpgmakerweb.com/index.php?threads/whtdragons-animals-and-running-horses-now-with-more-dragons.53552/

7. Chiken Sounds: "Collection of sound effects found in Minecraft" Available at: https://minecraft.gamepedia.com/Category:Sound_effects

