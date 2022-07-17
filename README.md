# unity-snake-ar

A port of the existing "Snake 2D" game to the "Snake AR" game. The base code was taken from [here](https://sharpcoderblog.com/blog/snake-game-in-unity-3d), which was then used to actually port it to an AR application.

You can watch the demo of the project [**HERE**](https://www.youtube.com/watch?v=tOHxG8_DrI0).

## How to test it

If you want to test it in **Unity Editor**:

- import the project and open it via **Unity 2019.4.20f1**
- in the *Project* window, go to *Assets* -> *Scenes* and drag *SnakeGameScene* file to the *Hierarchy* window
- in the *Hierarchy* window, remove *Untitled* scene
- click *Play* button (make sure you have camera connected) and make sure [this](https://raw.githubusercontent.com/MrPatrek/unity-snake-ar/main/Assets/Editor/Vuforia/ImageTargetTextures/Snake_Game_AR/stones_wid12_scaled.jpg) picture is visible in your camera
- game field should appear and you may start playing

If you want to test it from e.g. **Android** (like in the [demo](https://www.youtube.com/watch?v=tOHxG8_DrI0)):

- import the project and open it via **Unity 2019.4.20f1** with having **Andorid Build Support** installed (including **OpenJDK** as well as **Android SDK & NDK tools**)
- go to *File* -> *Build Settings*
- choose *Android* and click *Switch Platform*
- click *Build* and save the corresponding APK file, which you should then open on your Andorid device and install the app
- open the app on your Android device and make sure [this](https://raw.githubusercontent.com/MrPatrek/unity-snake-ar/main/Assets/Editor/Vuforia/ImageTargetTextures/Snake_Game_AR/stones_wid12_scaled.jpg) picture is visible in your camera
- game field should appear and you may start playing
