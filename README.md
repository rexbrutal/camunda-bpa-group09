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

Assign the "Order-to-Cash BPMN process model" as the main process (three points on the left side inside the project
Create a cluster
Open main process
Deploy to cluster
Click on "Run"
Use input.json as input in the "Variables" field in Run
Click on run
See the process

## Screencast

The screencast can be found either linked in the report or here: https://box.hu-berlin.de/d/13e3f6c06ca5408b9cab/

## Running in Camunda

To run the process in Camunda first deploy and then run an instance. When asked for a variable please use the following example of a run variable:

{
    "example_order": {
        "items": [
            {
                "product": "pencil",
                "orderCount": 10,
                "stockCount": 8,
                "cost": 1.0
            },
            {
                "product": "tablet",
                "orderCount": 1,
                "stockCount": 20,
                "cost": 180.49
            },
            {
                "product": "soccerball",
                "orderCount": 2,
                "stockCount": 96,
                "cost": 22.50
            }
        ],
        "customer": {
            "name": "PeterParker",
            "address": "Rudower Chausee",
            "number": 26,
            "postal_code": 12489,
            "city": "Berlin",
            "email": "your-email-here"
        },
        "duration": 2
    }
}
