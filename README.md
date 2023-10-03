# 101 Introduction to Unity Game Development

---

## Goal

In this introduction course to Unity Game Development, we'll implement a clone of [Impossible Game (Video)](https://www.youtube.com/watch?v=O_U65QkH_EU)

---

## Grading Criteria

### Passing Grade
All Baseline Milestones completed.

### Excellent Grade
All Advanced Miletones completed.

---

## Submission

Submit your project to Learnpoint by adding a link to your repository and/or a link to your game on Unity Play as well as uploading a Screenshot

---

## Baseline Milestone

### 1. Learn GitHub Basics

Please follow the instructions on these [Slides](https://docs.google.com/presentation/d/1n-Z-gE7qqa1ir8QF2eeyKuZbBgPQyeh_/edit?usp=sharing&ouid=107156420442105520882&rtpof=true&sd=true), but name your repository and Unity Project `ImpossibleGame` 

### 2. Build Ground

Place a few cubes in the scene to build a ground on which our player can navigate. Place the camera in a way, that it can see the ground. - Requires [Unity Essentials](https://learn.unity.com/pathway/unity-essentials)

### 3. Create Player

Place a cube on top of those cube. Name it Player.

### 4. Move Camera

Change the camera's position and rotation, so we can see the Player Cube on top of the Ground Cubes from the side or any other perspective that you prefer.

### 5. Player Movement

Make the player move from left to right permanently (without requiring any input) - Requires [Visual Scripting](https://learn.unity.com/project/introduction-to-visual-scripting?uv=2021.1)

### 6. Goal

Place a goal at the end of your ground cubes. Show a Log "You Win!" when the player touches that goal.

### 7. Long Level

Make your level so long, that it does not fully fit on the screen. Make the camera follow the player.

### 8. Spike

Add a spike in the level. When the player touches the spike, show a log: "You died!" and restart the game after 3 seconds

### 9. Player Jump

Allow the player to jump when pressing the SPACE-key.

### 10. Grounding

Make sure that the player can only jump while he is on ground. You can use `OnCollisionStay` or `RayCast` to do this.

---

## Advanced Milestone

### 1. Crash

Add cubes, that the player needs to jump on. If the player crashes into the cube from the side, he dies. If he lands on it, he survives.

### 2. Pretty, please?

Make it your own. Add some Assets from Unity's [Asset Store](https://assetstore.unity.com). If you can, add Effects and Sound.

### 3. Release

Publish your game to [Unity Play (Tutorial)](https://learn.unity.com/tutorial/creating-and-publishing-webgl-builds#601abb0cedbc2a0027bad0e3)


## Bonus

### 1. Counter

Add a counter that shows, how often you've tried this level. Print the Output to the Log. 


## Skills Learned

<details>
  <summary>Click me</summary>
  
### Git
- Repository
  - Create a local one
  - Publish it to GitHub
- Commit
- Push 

### Unity 
- Hub
  - Install an Editor
  - Create a Project
  - Open a Project
- Editor
  - Project View
  - Hierarchy View
  - Scene View
  - Game View
  - Inspector
  - Meta-Files
  - PlayMode
  - Console
- Engine
  - GameObject
  - Component
  - Asset
  - Scene
  - Prefab
- Components
  - Transform
    - Position
    - Rotation
    - Scale
    - Parent
  - Camera
  - DirectionalLight
  - Canvas
  - RectTransform
    - Anchor
    - Pivot
  - TextMeshProUGUI
    - Text
  - Image
- Packages
  - Manifest
  - Visual Scripting
- Build
- Play
  
### Game Engine
- Update
  - DeltaTime
  - Frames per Second
- FixedUpdate

### Physics
- Collider
  - Trigger
  - Events
- Rigidbody
  - Velocity
  - Force
- Raycast

### Maths
- Vector3
  
</details>
