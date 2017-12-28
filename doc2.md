# Anna
---
### ADDITION OF NEW FEATURES

To every new feature added in the Anna-Chrome Extension, first it must be declared as an **INTENT** in the corrosponding API agent.The background.js contains the main code and acts as a platform to addition of new features.

**TO ASSIGN ANNA A NEW FEATURE**  
To assign **_ANNA_** a new feature is pretty simple! :smiley:   
Once you open the _background.js_ file you will find under _tasks()_ function the similar kind of _else if_ statements are used.One might think this as a code snippet.  

> }else if (data.result.metadata.intentName === "INTENT_NAME") {  
> action to be performed.

The usuage of **else if** statement is for obvious reasons ,it checks for the Intent by it's name and accordingly performs the operation. 

#### Followings steps can be taken into consideration for the ADDITION OF NEW FEATURE  
* Think something creativity that can be added as a feature.
* Create the corrosponding INTENT in the API.
* Tweak the code and assign the desired chrome operation to it.
* Allot the permission in _manifest.json_ file,if the chrome operation needs any permission.
* You are done.:+1:

#### NAMING CONVENTION
We all love consistency in the code.In order to tweak code or modify we ensure that we should not get baffled among the thousands of code thereby we go for a particular naming convention.We are proud to say that we too follow a particular naming convention with proper indentation of code so that a new contributor does not get confused with the flow of the code amd can easily contribute to the project.

 * **VARIABLES**  
   
   For variables we love to use "inner caps" for Multiple-Word Names.  
   For instance,look below at the code extracts taken from _background.js_.  
   
   > var byteString;  
   >var baseUrl = "https://api.api.ai/v1/";  
   >var targetId = null;  
   
   _The variable name should be relevent with the type of action to which that variable is used for._  
   
 * **FUNCTIONS**  
   
   For naming functions we too opt "inner caps" method for Multiple-Word Names.  
   For reducing the number of lines of code we love to put the starting parenthesis at the end of every function name only when the body of function is to be wriiten.   
   For instance,look below at the code extracts taken from _background.js_.  
   
   >function takeScreenshot() {  
   >function processIt(data) {    
   
    _The function name should be relevent with the type of operation it is to be performed._  

## CONTRIBUTING  

If you wish to help,develop and contribute to **ANNA** follow up the below given guidelines-

## Getting started
Before you get started, make sure you have:

  * [Installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  and [Configured](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
  Git on your local machine

  * Registered with a [GitHub account.](https://github.com/signup/free)
  
Fork the [Anna repository](https://github.com/Anna-Assistant/Anna) on your GitHub Account and check out the [issues](https://github.com/Anna-Assistant/Anna/issues) section.  
Pick up with any issue which you want to contribute and do comment it right there. Once, we will assign you with the issue that you picked up,pace up your strategy and get yourself ready to contribute. For any queries do not hesitate to ask via our zulip channel

                                      
**WE WOULD:heart:TO HEAR SOME INNOVATIVE FEATURES FROM YOU.**


