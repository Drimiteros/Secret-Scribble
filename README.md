# Secret Scribble
Is an offline password manager for Windows. It has basic features that you will find in the most popular ones, along side with some unique! You can see more detailed information of its official webpage **(https://secretscribble.42web.io)**

## Linking steps:
1. You will need to download and link SFML 2.6.0 **(https://www.sfml-dev.org/download/sfml/old-versions.php)**. You can follow this useful video to guide you through the linking proccess **(https://www.youtube.com/watch?v=WoVoIhgutMU)**

2. You will need to download and link a custom version of ImGui that works with SFML **(https://github.com/SFML/imgui-sfml)**. You can follow this useful video to guide you through the linking proccess **(https://www.youtube.com/watch?v=2YS5WJTeKpI)**
   
3. You will need to download and link the Cryptopp library **(https://github.com/weidai11/cryptopp)**. You can follow this useful video to guide you through the linking proccess **(https://www.youtube.com/watch?v=5XE4zEN-WKg)**

## Explain the use of the external libraries:
1. SFML handles graphics, audio and networking. It will allow us to easily make custom UI and use its networking feature for password sharing in the future. 

2. ImGui is a UI library, but we only use it for its advanced text editor feature.

3. Cryptopp handles all the encryprion. It provides all the juicy encryption-decription algorithms!

## Current Bugs & Problems
[ x ] Currently your master password is stored by getting encrypted with a pre-defined hardcoded password which is not the best practice. This will change in the future.
