# Repositories
- Skymap **SERVER**: [https://github.com/alcance/skymap-server/tree/master] 
- Skymap **CLIENT**: [https://github.com/alcance/skymap-client/tree/master] 

# Overview
* Show user a live map of **locations** fetched from a external store.
* See a **map** around given locations.
* Get **live updates** if data is changed in the backend
* Each **location** at giver **latitude** and **longitude** should whow the **name** of the **location** an a **status** if is open or closed.
* Frontend updates **locations** realtime.

# Notes
![Alt text](assets/note1.JPG?raw=true "Arquitecture")
![Alt text](assets/note2.JPG?raw=true "Mockup")

# Arquitectura
![Alt text](assets/diagram.png?raw=true "Diagram")

# Mockup


# Technology Stack
* Node
* Express
* SocketIO
* Redis
* Angular
* Docker

![Alt text](assets/code_cli.png?raw=true "Mockup")

# Screenshots
![Alt text](assets/screen_webapp.png?raw=true "Mockup")

# Nice to have
* TDD
* More modularity

# Known bugs
* When you send a random location and it does not exist. It will not display anyting.

# TODO
- [ ] Deployment
