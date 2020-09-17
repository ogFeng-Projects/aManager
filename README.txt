Created by Josh (ogFeng) 

Installation/Implementation Instructions:
1 - Create a dedicated audio manager gameObject in scene
2 - Drag/drop "aManager.cs" onto gameObject
3 - Start adding audio sources through the array lists

To use audio sources within the audio manager...
1 - Go into specific script that will play the audio source and use line...
2 - FindObjectOfType<AudioManager>().Play("PlayerDeath");
4 - AudioManager References this script while playerdeath references the audio clip created