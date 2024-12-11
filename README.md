# camunda-bpa-group09
Deliverable 2 of the group 09 for the course "Busine Process Automation" at the university of Humboldt-University at Berlin.

## Instructions

Since we do not have any backend code with e.g. springboot or similar there is not really a need for instructions after the model has been imported into Camunda.

To import the model in Camunda 8, first sign up in camunda: https://camunda.com/de/
Make sure to choose the free trial when signing up since this can't be changed afterwards.

After creating an account, click on the menu button (upper left corner at the moment) and select "Modeler"
Now create a new project (e.g. "BPA Group 9") and click on the project 
Download the model and forms from GitHub
Upload the files via the "Create new" -> "Upload files" Button

Assign the "Order-to-Cash BPMN process model" as the main process (three points on the left side inside the project)
Create a cluster

Open the main process "Order-to-Cash BPMN process model"
Click "Deploy" on the upper right side
Choose the created cluster and click "Deploy"

Next click on "Run" on the upper right side next to "Deploy"
Use input.json as input in the "Variables" field inside Run (pop-up window is called "Start instance")
Just copy-paste the content of the file into the field

Click on run (after filling the "Variables" field)

See the process being executed in the Instance by clicking "View process instance" (small pop-up window with a link in the middle at the bottom of the screen)
New tab with the running instance opens

* See Screencast on how to simulate the example order *

### More information:

Green means executed (flow/arrows) - White means not yet executed

To open the tasklist 
- either click on a user task and click on "Open Tasklist" in the pop-up window
- or click on the menu and select "Tasklist"


## Screencast

The screencast can be found either linked in the report or here: https://box.hu-berlin.de/d/13e3f6c06ca5408b9cab/


