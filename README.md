# TaskWebAPI
Web APIs for CRUD operations of task

**TaskDTO.cs**

Contains structure of Task data

**TaskData.cs**

Contains dictionary that contains task data in dictionary dctTask

**TaskActions.cs**

Contains functions for all required actions on task data (functions of this file will be called from APIs)

Function list

GetAllTask- to get list of all task

CreateTask- to create new task (single/multiple)

EditTask- to edit existing task (single/multiple)

DeleteTask- to delete existing task (single/multiple)

GetAllTaskFromDB - to get list of all task from DB

CreateTaskInDB - to create new task in DB (single/multiple)


**TaskController.cs**

Contains APIs for performing actions on task data

API list

api/task/getalltask- to get list of all task

api/task/createtask- to create new task (single/multiple)

api/task/edittask- to edit existing task (single/multiple)

api/task/deletetask- to delete existing task (single/multiple)

api/task/getalltaskfromdb - to get list of all task from DB

api/task/createtaskindb - to create new task in DB (single/multiple) 
