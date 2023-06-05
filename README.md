# Unreal-EXNO-6-Implement-the-AI-random-movement
## EXNO 6
Implement the AI random movement

## Aim:
To create a Unreal project That have   AI character To Chase the Player 

## Procedure:
1.	Open Unreal Engine and create a new Blueprint project.
2.	Create a Blueprint class for your character:
•	Right-click in the Content Browser and select "Blueprint Class."
•	Choose "Character" as the parent class.
•	Name the Blueprint as desired.
3.	Create a Blueprint class for the AI controller:
•	Right-click in the Content Browser and select "Blueprint Class."
•	Choose "AI Controller" as the parent class.
•	Name the Blueprint as desired.
4.	Open the AI controller Blueprint:
•	In the Event Graph, right-click and search for "Blackboard."
•	Add a "Blackboard" node to the graph and name it "MyBoard."
5.	Open the Blackboard:
•	Create a new Key named "TargetLoc" with the Vector data type.
6.	Create a Behavior Tree (BT) Blueprint:
•	Right-click in the Content Browser and select "Blueprint Class."
•	Choose "Behavior Tree" as the parent class.
•	Name the Blueprint as desired.
7.	Open the Behavior Tree Blueprint:
•	Create a sequence node by dragging and dropping it from the palette onto the graph.
•	Connect the sequence node to the root node.
8.	Add a "Move To" task to the sequence:
•	Drag and drop the "Move To" task from the palette onto the graph.
•	Connect the output of the sequence node to the input of the "Move To" task.
9.	Add a "Wait" task after the "Move To" task:
•	Drag and drop the "Wait" task from the palette onto the graph.
•	Connect the output of the "Move To" task to the input of the "Wait" task.
10.	After completing all the steps, place the AI character in the viewport:
•	Drag and drop the AI character Blueprint into the viewport to place it.
•	Ensure that the third-person character is also present in the scene for the AI character to chase.
## OUTPUT:


## Content browser:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/c3f77733-1a3c-4d4e-a590-de180b4debea)

 
## Third_Person character:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/a6ac5ff2-4e60-45fe-931d-ae1da5792a62)

 

## AI character:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/8c93e4b3-8b99-4d7b-b668-8a4d6091d66b)

 
## AI Controller Event graph:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/bb184147-fb39-4235-bfc3-caa443ab74e1)

 

## MY Black Board:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/bb3b72a5-dc1a-4447-9b90-8124b04f4424)
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/aafcb3d7-05ba-4e2b-95a2-b52da874a1e1)

              
## MY Behavior tree:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/1ec63d15-040d-4ff1-b76f-69722505e5db)

 
## Service: 
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/31f5c406-6a81-4191-979e-220c80131672)

 

 Prethi>ee
## AI Movement:
![image](https://github.com/Prethiveerajan/Unreal-EXNO-6-Implement-the-AI-random-movement/assets/94233064/425ea87f-0d69-436f-a257-ff8c3ccbf776)

 

## Results:
Thus we successfully created a Unreal project That have   AI character To Chase the Player 




