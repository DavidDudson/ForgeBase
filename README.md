# ForgeBase

Perfect example of how to create a multiproject build shell for MinecraftForge 1.9.

How to use:

- Install gradle locally (Personal preference, you could use a wrapper if you wish)
- Fork this repository
- run gradle setupDecompWorkspace
- Create your mod folders

Example Directory Structure
Minecraft/
  Forge/ (This repo)
    build.gradle
    settings.gradle
  ProjectA/
    build.gradle
  ProjectB/
    build.gradle

- IDE Setup:
  - Import the Forge/build.gradle into either eclipse or intellij
  - If you are using IntelliJ you will be able to open the gradle toolbar and select the appropriate
