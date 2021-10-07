# Requirements for external task clients for Camunda Platform

## A document to help building your own external task client for Camunda Platform by providing the requirements and useful sources

The following document list the requirements for an external task client for Camunda Platform. It distinguishes between minimum requirements and additional features. It can help to build a new External Task Client or to evaluate External Task clients from the community.

## Sources
- [Camunda Platform's REST API for External Tasks](https://docs.camunda.org/manual/latest/reference/rest/external-task/)
- [Java External Task Client maintained by Camunda](https://github.com/camunda/camunda-bpm-platform/tree/master/clients/java)
- [JS External Task Client maintained by Camunda](https://github.com/camunda/camunda-external-task-client-js)
- [List with External Task Clients from the Community](https://github.com/camunda/awesome-camunda-external-clients)

## Requirements

|Feature|Must include|Optional| 
|---|---|---|
|Client object|:white_medium_square: URL Endpoint for the Camunda Engine <br> :ballot_box_with_check: Worker ID | :ballot_box_with_check: Maximum number of tasks to work on from the Camunda Engine <br> :ballot_box_with_check: Lock Duration of a task <br>  :ballot_box_with_check: Long polling <br> :ballot_box_with_check: Fetch task based on their priority <br> :ballot_box_with_check: Automatic polling <br> :ballot_box_with_check: Define interval for polling <br> :ballot_box_with_check: Create Readable WorkerID |




