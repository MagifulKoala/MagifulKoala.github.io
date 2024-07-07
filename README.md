# Pablo Dorado

Hi ! My name is Pablo and I am a computer scientist with great interest in videogame development and AI. Here you'll find some of my work from videogame development to AI and data science. 

- [Game Development](#game-development-projects)
- [Artificial Intelligence](#ai-projects)
- [Art](#art)

# Game Development Projects

## [Absolute Conflict](https://github.com/MagifulKoala/Absoulte-conflict)
A project that aims to bring an intense and immersive conflict simulation with mechanics similar to Total War. The project is still in development

![](https://github.com/MagifulKoala/MagifulKoala.github.io/blob/main/images/thumbnail.png?raw=true)

[Absolute Conflict github link](https://github.com/MagifulKoala/Absoulte-conflict/)

</details>

<details>
  <summary> Absolute Conflict - More information </summary>

  <h4>Goals</h4>

  <ul>
    <li> <strong>UI</strong> </li>
    <p> Players must be able to assemble an army and effectly interact with the UI to control it and battle agaisnt an opponent. </p>
    <li> <strong>Accurate Unit Deployment</strong> </li>
    <p> Depending on unit size and spawn restrictions the unit must be able to spawn with no errors in the field of battle. On spawn, units take a rectangular formation with rows and columns of soldiers </p>
    <li> <strong> Unit Point Movement </strong></li>
    <p> Once deployed units must be able to move as a whole towards its destination point </p>
    <li> <strong>Unit Combat</strong> </li>
    <p> Rudimentary combat between units. Soldiers within each unit must be able to enter combar with opposing units. As soldiers die new soldiers must take their place until there are no soldiers left </p>
  </ul>
  
  <h4> <strong> Challenges </strong> </h4>
    <p>Even though Unity has options to directly manipulate the local transformation of an object, I decided to work with global transformation as a challenge. This decition put to test my linear algebra skills.
For example, in order to move the camera effectively through the combat zone I had to keep in mind where the local 'z' axis of the camera was so that I could apply the appropiate translation vector. In order
to do this I used a rotation matrix to determine the local forward vector. To define the rotation Matrix matrices corresponding to the x,y and z rotation were multiplied. Since matrix multiplication is non-commutative I was puzzled to which combination to use. I had to go into the Unity documentation and find out their definition for euler angles. Once I had that I was able to correctly create the rotation matrix. As I mentioned before,
the rotation matrix allowed me to define the forward facing vector of the camera. Once I had this vector not only was I able to move the camera effectly buy raycast from the camera in that direction could be cast in order to controll the different units in the game. </p>
  
</details>


## [VR The Hands of Midas](https://github.com/MagifulKoala/VRProyectoDeGrado)
A Virtual Reality project developed for academic purposes. This repository showcases a comprehensive VR environment. The game was designed and implemented with the main objective of exploring new techniques
or mechanics that add value to virtual reality in video games. In this sense, the developed game was titled "The Hands of Midas". The main mechanic of the game was centered in the transmutation of object materials. The player has the ability to acquire the properties of a material by
touching it with their left hand and can convert any object they touch with their
right hand into that material. In this way, the game is a single-player puzzle in
which the player must transmute the materials of various objects within their environment to solve puzzles and progress through levels. The game was developed
in Unity in one-week sprints throughout a span of 4 months.

![](https://github.com/MagifulKoala/MagifulKoala.github.io/blob/main/images/Thumbnail.png?raw=true)

[VR The Hands of Midas github link](https://github.com/MagifulKoala/VRProyectoDeGrado/)

<details>
  <summary>VR The Hands of Midas - More Information</summary>
  <h4>Goals</h4>

  <ul>
    <li> <strong>Some Goal</strong> </li>
    <p> some description </p>
    <li> <strong>Some Goal 2</strong> </li>
    <p> some description 2</p>
  </ul>
  
  <h4>Challenges</h4>
  
  <ul>
    <li> <strong>Some challenge</strong> </li>
    <p> some description </p>
    <li> <strong>Some challenge 2</strong> </li>
    <p> some description 2</p>
  </ul>
  
</details>

## [Last Stand](https://github.com/MagifulKoala/LastStand)
An action-packed game where players must defend themselves against a horde of undead enemies. The game was developed for the 2024 GameDev.TV game jam. The project is still in development

![](https://github.com/MagifulKoala/MagifulKoala.github.io/blob/main/images/newThumbnail.png?raw=true)

[Last Stand github link](https://github.com/MagifulKoala/LastStand/)
[play now](https://magifulkoala.itch.io/the-last-stand)

<details>
  <summary>Last Stand - More Information</summary>
  <h4>Goals</h4>

  <ul>
    <li> <strong>Some Goal</strong> </li>
    <p> some description </p>
    <li> <strong>Some Goal 2</strong> </li>
    <p> some description 2</p>
  </ul>
  
  <h4>Challenges</h4>
  
  <ul>
    <li> <strong>Some challenge</strong> </li>
    <p> some description </p>
    <li> <strong>Some challenge 2</strong> </li>
    <p> some description 2</p>
  </ul>
</details>

# Extra links
### [my itch.io](https://magifulkoala.itch.io/)

# AI Projects
-  [DeepLearning](#deep-Learning)
-  [DataScience](#Data-science)

## Deep Learning
## Data Science

# Art


