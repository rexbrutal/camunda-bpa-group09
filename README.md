# camunda-bpa-group09
Deliverable 2 of the group 09 for the course "Busine Process Automation" in the university of Humboldt University at Berlin.

## Instructions

Since we do not have any backend code with i.e. springboot or etc. there is not really a need for instructions.

## Screencast

The screencast can be found either linked in the report or here again: https://box.hu-berlin.de/d/13e3f6c06ca5408b9cab/

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
            "email": "bpa.hu.ws2425@gmail.com"
        },
        "duration": 2
    }
}
