
### Class: User

###### Responsibilities

- Represents each user of the app

###### Collaborators

- Entrant
- Organizer
- Admin


### Class: Entrant

###### Responsibilities

- Holds info about an Entrant

###### Collaborators

- WaitList
- Event
- Organizer

### Class: Event

###### Responsibilities

- Holds info about event

###### Collaborators

- WaitingList
- Entrant
- Organizer



### Class: WaitingList

###### Responsibilities

- Contains a list of wait entrants for the event

###### Collaborators

- Entrant
- Event
- Organizer



### Class: Organizer

###### Responsibilities

- Creates and manages events

###### Collaborators

- Entrant
- Events
- WaitingList



### Class: Administrator

###### Responsibilities

- Controls events listed, profiles, images, organizers

###### Collaborators

- Events
- Notifications
- Collaborators
- Profile


### Class: Profile

###### Responsibilities

- Holds info such as name, email and optional phone number

###### Collaborators

- Entrant
- Administrator


### Class: Notification  

##### Responsibilities

- Sends info to users

##### Collaborators

- Administrator
- Entrant
- Organizer


### Class: Map

###### Responsibilities

- Display location info of entrants

###### Collaborators

- Entrants
- Organizer