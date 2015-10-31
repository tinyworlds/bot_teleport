Behind the scenes of a Twitter teleportation device

### How does it work?
- the teleport bot is running using http://cheapbotsdonequick.com/
- it has several "plots" and several words/sentences to create variations of those "plots"  

#### Example
Here is a very simple example "plot":
```
"origin":[#start# #attributes# #places#]
```
The hashtags on each side tell the tool to choose a random item of a referenced list.
For example for #start#, the tool would look up the list called "start" and choose a random item out of it.
This simple procedure makes the code:
```
"origin":[#start# #attributes# #places#]
```
turn into something like this:
``` 
You discover a magical tower
```
  
There is also a great tutorial if you'd like to learn more: http://www.crystalcodepalace.com/traceryTut.html  
<b> This repository is licensed as CC0/Public Domain - do whatever you want with it! </b>
