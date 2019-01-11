# Udacity Carnival
Project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Project: Udacity Carnival
- Course: Introduction to Virtual Reality
- Submission by: Jordan Dobson
- Summary: I updated Coin Toss to still allow for over and under shooting so you have to hit it right with values from the Navigation Quiz. The Wheel values are updated appropriately for their width as well as the plinko game was updated to move the puck side to side to 0.7 which is shown when succesfully landing a coin in coin toss. The Bear is also moved so it doesn't land on the camera. My name is also set to fit within the boundaries of the game board.

[Download Project Files](https://drive.google.com/file/d/1HcxBh31tauIMbgCF1WiUx1n5YedDXUzT/view?usp=sharing)


### Versions Used
- [Unity LTS Release 2017.4.15](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.170.0)
- [TextMesh Pro](https://assetstore.unity.com/packages/essentials/beta-projects/textmesh-pro-84126) v1.2.2


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is not included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.
