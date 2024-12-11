# Ü2 – BPMN Specification with Camunda Exercise
Deliverable 2 of Group 09 for the course "Busine Process Automation" at the university of Humboldt-University at Berlin.

## **Instructions**

### Importing the Model into Camunda 8

Since we do not have any backend code with e.g. Spring Boot or similar, there is not really a need for instructions after the model has been imported into Camunda.

1. To import the model in Camunda 8, first sign up in Camunda: https://camunda.com/de/
2. Make sure to choose the free trial when signing up since this can't be changed afterwards.


### Setting Up Your Project

1. After creating an account, click on the menu button (upper left corner at the moment) and select "Modeler."
2. Now create a new project (e.g., "BPA Group 9") and click on the project.
3. Download the model and forms from [resources](resources/).
4. Upload the files via the "Create new" -> "Upload files" Button.
5. Assign the "Order-to-Cash BPMN process model" as the main process (three points on the left side inside the project).


### Creating a Cluster

1. Open the menu and click on "Console."
2. Click on "Clusters" in the tab (Dashboard - Clusters - Organization) next to the menu.
3. Create a new cluster ("Create new cluster"):
   - Cluster name: "Test cluster"
   - Channels: Alpha (1)
   - Generations: Zeebe (8.7.0)

### Simulation

* * *

See [Screencast](https://github.com/rexbrutal/camunda-bpa-group09/blob/main/README.md#screencast) on how to simulate the example order!

* * *

Or follow these steps: 

- Open the main process "Order-to-Cash BPMN process model" in "Modeler"

- Click "Deploy" on the upper right side

- Choose the created cluster and click "Deploy"

- Next click on "Run" on the upper right side next to "Deploy"

  - Use this [input](input.json) in the "Variables" field inside Run (pop-up window is called "Start instance")

  - Just copy-paste the content of the file into the field

  - Click on run (after filling the "Variables" field)

  - See the process being executed in the Instance by clicking "View process instance"
    (small pop-up window with a link in the middle at the bottom of the screen)

- New tab with the running instance opens

  - Handle the user tasks in the tasklist (To open the tasklist either click on a user task and click on "Open Tasklist" in the pop-up window or click on the menu and select "Tasklist")
 
  - You can see the variables and executued tasks in the running instance (Green means executed (flow/arrows) and white means not yet executed)
 
  - After reaching the end event, no tasks should be left in the tasklist
 
  - Click on the red highlighted "delete" on the upper right corner to delete the instance

## Screencast

The screencast can be found either linked in the report or here: https://box.hu-berlin.de/d/13e3f6c06ca5408b9cab/

***

## **🥳 Congratulations!** 🥳


You successfully simulated a **Nozama Order**! 🎯💼

### 🤠 We tip our hats to You! 🤠

Great work! You've shown exceptional skill in the world of shopping simulations. 🤓💻

### 😎 Stay cool and Shop again! 😎

At Nozama, we value your "virtual" patronage and can't wait to see you back for another shopping adventure. 🛒✨

## **What can You do next?** 🛠️

- **Explore the Code:** Dive into the repository and see how things work behind the scenes. 🧑‍💻🔍
- **Give Us a Star:** If you like this, don’t forget to star the repo! ⭐
- **Create More Simulations:** Tinker, tweak, and simulate some more. Endless possibilities await! 🚀

---

### 🌟 Happy shopping and coding! 🌟
