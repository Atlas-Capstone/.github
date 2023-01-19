Next generation fitness app, using React, Rails, Tailwind, and TypeScript.

Project link: :earth_asia:

- [See our database schema](https://docs.google.com/document/d/120WrZ5LZB7vedFtjZQTNwbVa-6HexhsKH7_FsS0D6Qo/edit?usp=sharing)
- [Trello](https://trello.com/b/3rkEvjWA/atlas)
- [Slack](https://app.slack.com/client/T04B40L2C/C04JP9SFVLK)
- [Figma](https://www.figma.com/file/jtnyZbNAbNW0OrKsD7tOmE/Atlas-Mobile-UI?node-id=0%3A1&t=cLJG6UqbgYZMIeGD-0)
- [E-mail](mailto:atlascapstone@gmail.com)
- [Read our elevator pitch](https://docs.google.com/document/d/1WqmMvFAsR7GZbPTTVP2ReWBhZAY786r3GGlNZy6b8vU/edit?usp=sharing)
- [Read our database schema](#database-schema)

``` ruby
Welcome to Team Atlas
Meet our team members!
```

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
- Zoom logo animation
- Website flowchart
- Ensures the README contains appropriate information (beautify, add navigation)
- Gives progress updates to the class at the end of the day.

---
# Database Schema
---

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

