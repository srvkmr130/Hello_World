# Anna
---
### ADDITION OF NEW FEATURES

To every new feature added in the Anna-Chrome Extension, first it must be declared as an **INTENT** in the corrosponding API agent.The background.js contains the main code and acts as a platform to addition of new features.

**TO ASSIGN ANNA A NEW FEATURE**  
To assign **_ANNA_** a new feature is pretty simple! :smiley:   
Once you open the _background.js_ file you will find under _tasks()_ function the similar kind of _else if_ statements are used.One might think this as a code snippet.  

> }else if (data.result.metadata.intentName === "INTENT_NAME") {  
> action to be performed.

#### Followings steps can be taken into consideration for the ADDITION OF NEW FEATURE  
* Think something creativity that can be added as a feature.
* Create the corrosponding INTENT in the API.
* Tweak the code and assign the desired chrome operation to it.
* Allot the permission in _permission.js_ file
* You are done.:+1:


The usuage of else if statement that it checks for the new intent and accordingly performs the operation. 

