# Pablo Dorado

Hi ! My name is Pablo and I am a computer scientist with great interest in videogame development and AI. Here you'll find some of my work. 

- [Artificial Intelligence](#ai-projects)
- [Game Development](#game-development-projects)

# AI Projects

-  [DeepLearning](#deep-Learning)
-  [DataScience](#Data-science)

## Data Science

### [House Prices - Advanced Regression Techniques](https://www.kaggle.com/code/doradopablo/house-prices-random-forest-and-xgboost)
The House Prices - Advanced Regression Techniques Kaggle competition, as the name suggests, is centered around predicting the final price of a set of homes given 79 exploratory variables describing (almost) every aspect of residential homes in Ames, Iowa. The Ames Housing dataset by Dean De Cock was used for this project. In this sense the project followed the traditional machine learning process and was composed of data preprocessing, modeling and evaluations phases. You can find more information about the project below. 

![](https://raw.githubusercontent.com/MagifulKoala/MagifulKoala.github.io/main/images/housePricesHeader.png)

[![Project](https://img.shields.io/badge/Kaggle-Project-blue.svg)](https://www.kaggle.com/code/doradopablo/house-prices-random-forest-and-xgboost)


<details>
  <summary>House Prices - More Information</summary>

  <h4>Description</h4>
    <ul>
      <p>As mentioned previously, the project centered around the prediction of house prices given 79 features. In this sense, regression techniques were applied in order to do this. The project was divided into three parts. The first being the data preprocessing phase, which you can find more information on in the challenges section of this project. Second, the modeling part and finally the evaluation. For data preprocessing the data was cleaned and split into training and test sets. For modeling I decided to apply random forest regression. This model improves robustness and accuracy by averaging multiple trees, reducing overfitting in contrast to decision tree regression. Additionally the model doesn’t require feature scaling and generally speaking works well on both linear and nonlinear problems. Finally, from experience, houses with similar features tend to have roughly similar prices given they are in close locations. In this case all houses are from Ames, Iowa. Therefore I considered random forest to be a good fit. In order to find the best parameters for the model grid search was applied. Finally during model evaluation the regressor got an r2 score of 0.84 and a rsme of 33551 given that the average house price was of 180921 with a standard deviation of 79442. </p>
    </ul>
  <h4>Challenges</h4>
    <ul>
      <p>The most challenging and time consuming part of the project was data cleaning. The modeling and evaluation parts of the project were straightforward once the data was clean. Before the data could be cleaned I had to make myself familiar with the dataset itself. This meant going through most of the columns and understanding what they represented. Next I found null values and had to determine the cause of said null value in order to know how to handle them. Fortunately, for this project most null values were caused because said feature was absent in the property. For example, a house without a basement or fence would have all corresponding columns for that feature as null. In this way, I replaced all null values corresponding to string as NA and numerical values for -1. Of course, in order to implement most of the regression models string columns had to be one hot encoded. After processing null values, separating, processing and rejoining data frames and encoding strings I was able to model, evaluate and predict. Given the fact that I was working with a rather large number of features (79), this process took quite a while to complete. By the end of the process I ended up with roughly 330 features.</p>
    </ul>
</details>


# Game Development Projects

## [Absolute Conflict](https://github.com/MagifulKoala/Absoulte-conflict)
A project that aims to bring an intense and immersive conflict simulation with mechanics similar to Total War. The project is still in development

![](https://github.com/MagifulKoala/MagifulKoala.github.io/blob/main/images/thumbnail.png?raw=true)

[Absolute Conflict github link](https://github.com/MagifulKoala/Absoulte-conflict/)


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
[![Watch the trailer](https://img.shields.io/badge/Watch%20Trailer-red?style=flat&logo=YouTube&logoColor=white&labelColor=grey)](https://youtu.be/WPqeUfSemp4)


[VR The Hands of Midas github link](https://github.com/MagifulKoala/VRProyectoDeGrado/)

<details>
  <summary>VR The Hands of Midas - More Information</summary>
  <h4>Goals</h4>

  <ul>
    <li> <strong>Functional material transmutation mechanics</strong> </li>
    <p> Successfully implemented material transmutation mechanics allowing the player to interact with a wide variety of materials and transmute their properties between them. Each material has its own properties and can effectively interact with other materials and, in some cases, with its environment.</p>
    <li> <strong>Functional level management and progression</strong> </li>
    <p>Successfully implemented various levels. Each level has its own level control that successfully handles dialogue with npc, progression, triggering events and puzzle mechanics, among others.</p>
    <li><strong>Functional VR rig</strong></li>
    <p>Functional VR rig that the player can control easily and that minimizes factors such as motion sickness. The rig implements player movement controls such as teleportation and joystick movement. Haptic feedback is available. 3d physics based functional hands models are implemented.</p>
  <li><strong>Interactable assets and levels</strong></li>
  <p>Implemented various  assets and props for level and puzzle construction. Most props can interact with other props and the environment and hold material transmutation mechanics. Added custom shaders to props the player can interact with in order to make them more visible during gameplay. 
</p>
 </ul>
  
  <h4>Challenges</h4>
  
  <ul>
    <li> <strong>VR motion sickness and playtesting</strong> </li>
    <p> Among the many challenges faced during the development of this project there are 3 major ones worth a mention. The first one was a time constraint linked with a lack of experience with VR development. This was my first project involving VR in game development and the project was expected to be fully functional at the end of a 16 week period. This meant I had to manage my time effectively to learn how VR was implemented while maintaining steady progress on the development of the game. Additionally, at the time of development, I had limited access to a VR headset, this meant I could only play test any builds at the end of the week. Finally, motion sickness is a very common problem with VR games. I had to manage available resources as much as possible to minimize the impact of motion sickness in gameplay. For example, I implemented fully functional, physics based, 3d hands on the player rig making the experience significantly smoother. </p>
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
    <li> <strong>functional game loop</strong> </li>
    <p>Turn in a game at the end of the jam with a fully functional game loop. In this case it meant being able to start the game, fight and survive waves of enemies while getting points from defeating them and eventually being overwhelmed and being defeated. From this point the player could see his final score and restart the game if they wished. Additionally have a functioning UI for the player to interact with the main menu, pause the game and quit.</p>
    <li> <strong>art & animations</strong> </li>
    <p>Create and successfully implement art and animations for all assets in the game. In this sense I created the background, enemies and props. The player and enemies both had functioning animation controllers in order to give a better gameplay experience. </p>
    <li><strong>Enemy AI</strong></li>
    <p>Implement functioning AI capable of following the player regardless of where they were located on the map, inflicting damage on them and being killed given points that add to the players’ final score in the end. </p>
  </ul>
  
  <h4>Challenges</h4>
  
  <ul>
    <li> <strong>solo game jam</strong> </li>
    <p>As mentioned in the description for the project, it was done for a game jam. Given the tight time constraints and the fact I was the only person working on the project I had to manage my time and resources to produce the best possible game I could make. I divided my schedule into pre production, production and postproduction. The preproduction took care of the planning and during the production phase I did most of the programming. A few days before submission I had finished most of the programming side of things. I only had to debug and optimize some aspects of the game. However I hadn't progressed in the art and animation side of things making the game functional but not really good to look at. This was a major challenge. In a couple of days I had to draw and animate all the assets for the game and debug what I could in the little time I had left. At the end I managed to turn into a functional state. However, I believe with better time management and foresight on how long the art and animation was going to take I could have gotten way better results.</p>
  </ul>
</details>

# Extra links
### [my itch.io](https://magifulkoala.itch.io/)
