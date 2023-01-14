Next generation fitness app, using React, Rails, Tailwind, and TypeScript.

Live link: :earth_asia:

- [Trello](https://trello.com/b/3rkEvjWA/atlas)
- [Slack](https://app.slack.com/client/T04B40L2C/C04JP9SFVLK)
- [E-mail](mailto:atlascapstone@gmail.com)
- [Database schema](https://docs.google.com/document/d/120WrZ5LZB7vedFtjZQTNwbVa-6HexhsKH7_FsS0D6Qo/edit?usp=sharing)
- [Elevator pitch](https://docs.google.com/document/d/1WqmMvFAsR7GZbPTTVP2ReWBhZAY786r3GGlNZy6b8vU/edit?usp=sharing)
- [User stories](https://docs.google.com/document/d/1iiF90WB4jrryqv8C88z0grxlvLB40FSURUGxH7U6ock/edit?usp=share_link)
``` ruby
Welcome to Team Atlas
Checkout our readme menu below!
```
[1. Team Members](#1-Team Members)
[2. Database Schema](#2-Schema)
---
# Team Members
## Design lead: Zeke
- Must have a strong understanding of the UI/UX needs of the application.
- Guardian of the wireframes.
- Oversees color schemes and implementation of branding.
- Ensures intuitive navigation and user experience.
- Explores styling libraries, responsive design, and accessibility features.
- Gives user status updates to the class at the end of the day.


## Project manager: Matt
- Must have strong communication with the team about who is working on what.
- Guardian of the Trello board.
- Ensures developers are assigned to the card they are working on.
- Notifies the instructors and/or mentors of PRs when a card is moved to the PR swimlane.
- Keeps Slack active with updates and pins appropriate content.
- Manages external resources.
- Gives status updates to the class at the beginning of the day.
 
 
## Tech lead/anchor: Garrett
- Must have a strong understanding of the technical needs of the project.
- Guardian of GitHub.
- Merges code when appropriate.
- Leads mentorship sessions for the team.
- Surfaces blockers to the class at the beginning of the day.


## Product manager: Frank
- Must have strong management skills to provide support to the team and keep team unblocked.
- Manages the conversation around large changes to the app.
- Ensures the README contains appropriate information.
- Gives progress updates to the class at the end of the day.
---
# Database Schema
### Users
:name :age :height :weight :gender
- have many Routines and Completed_Routines.
- can create Exercises.


### Routines
- are routines of Exercises Users access from the app.
- have many Exercise Routines.


### Exercises
:name :description :difficulty :category :image


### Exercise_Routines
- are user created custom routines of exercises
- have many exercises
- have many Completed_Routines


### Completed routines are part of stretch goals and are used to add a "timer" functionality
---
Footnotes
---
Project Image credit: By Jacob van Campen
https://www.paleisamsterdam.nl/en/discover-palace/atlas/, CC BY-SA 4.0,
https://commons.wikimedia.org/w/index.php?curid=121147230

Feel free to provide feedback in the discussions section
