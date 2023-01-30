
## Step 0:

Please refer to the [SETUP.md](./SETUP.md) file.

## Step 1 - Floor:

### 📑 **Description**:

in this step wee are gonna create a [3d object](https://docs.unity3d.com/Manual/class-GameObject.html) name floor and add a [script](https://docs.unity3d.com/Manual/Quickstart3DCreate.html#Scripting) to it 


### 📌 **Tasks**:

   - déplacé l'objet "floor" dans "prefabs"
   - créé un objet vide avec un script "floorgéneration"

<details> 
<summary>✔️ Result preview</summary>
<img src="" alt="backround image"/>
</details>

## Step 2 -generation de floor:

### 📑 **Description**:

In this step, we will use the [Instantiate()](https://docs.unity3d.com/ScriptReference/Object.Instantiate.html) function to create multiple instances of our floor object. We will also explore ways to generate the floor at specific locations in the scene.

### 📌 **Tasks**:

   - Use the Instantiate() function to create a floor at the position (0, 0, 0)
   - Create another floor at the position (10, 0, 0)
   - Experiment with different positions and rotations for the floor using the [Transform](https://docs.unity3d.com/ScriptReference/Transform.html) component

<details> 
<summary>✔️ Result preview</summary>
<img src="" alt="backround image">
</details>

## Step 3 - genere autour du joueur:

### 📑 **Description**:

In this step, we will use the [Vector3](https://docs.unity3d.com/ScriptReference/Vector3.html) class and the [transform.position](https://docs.unity3d.com/ScriptReference/Transform-position.html) property to generate the floor around the player as they move in the scene.

### 📌 **Tasks**:

   - Use the [Vector3.Distance](https://docs.unity3d.com/ScriptReference/Vector3.Distance.html) method to determine the distance between the player and the current floor.
   - Use the [transform.Translate](https://docs.unity3d.com/ScriptReference/Transform.Translate.html) method to move the floor towards the player.
   - Use the [Instantiate](https://docs.unity3d.com/ScriptReference/Object.Instantiate.html) function to generate new instances of the floor as the player moves in the scene.
   - Experiment with different values for the distance and speed of the floor generation.
   - Use the [Destroy](https://docs.unity3d.com/ScriptReference/Object.Destroy.html) function to remove the floor that is no longer needed.

<details> 
<summary>✔️ Result preview</summary>
<img src="" alt="backround image">
</details>

## Step 4 -random creation

### 📑 **Description**:

In this step, we will use the Vector3 class and [transform.position](https://docs.unity3d.com/ScriptReference/Transform-position.html) property to randomly generate the floor as the player moves in the scene. We will also use [Random.Range()](https://docs.unity3d.com/ScriptReference/Random.Range.html) to generate random positions for the floor.

### 📌 **Tasks**:

   - Créer aléatoirement un floor diferent autour du player lorsqu'il se déplace sur un nouveau floor

<details>   
<summary>✔️ Result preview</summary>
<img src="" alt="backround image">
</details>
