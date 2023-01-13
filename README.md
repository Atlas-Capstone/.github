# Tables

- Users
have many Routines and Completed_Routines
can create Exercises.

- Routines
have many Exercise Routines

- Exercises
have many Exercise_Routines

- Exercise_Routines
are user created cum routines of exercises
have many Completed_Routines


Completed routines are part of stretch goals and are used to add a "timer" functionality.


| User | Routines | Exercises | Exercise_Routines |
| --- | --- | --------------- |  --- |
| name | ------------- | name |  --- |
| age | ------- | description |  --- |
| height | ----- | difficulty |  --- |
| weight | ------- | category | --- |
| age | ------------- | image |  --- |
| gender | ------------ | --- | --- |
