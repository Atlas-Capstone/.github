# App building
- Initial documented setup
- ["Modifying devise" from Learn Syllabus, 'adding strong params'](https://github.com/learn-academy-2022-golf/Syllabus/blob/main/capstone/modifying-devise.md)
- Began following trello after this

# Tailwind
- Added classes to new.html.erb
``` css
class: "block text-sm font-md leading-5 text-white"
```

# Need to do
- Add gender options (select option)

# Database

## Users
:name :age :height :weight :gender
- have many Routines and Completed_Routines.
- can create Exercises.


## Routines
- are routines of Exercises Users access from the app.
- have many Exercise Routines.


## Exercises
:name :description :difficulty :category :image


## Exercise_Routines
- are user created custom routines of exercises
- have many exercises
- have many Completed_Routines


## Completed routines are part of stretch goals and are used to add a "timer" functionality
