# navsys - Documentation

**navsys** is a thesis project, which aims to provide an indoor navigation solution with audiovisual feedback, 
using a combination of smartphone based WiFi positioning and physical navigation units. 

## Documentation

### Thesis sources
In the thesis folder the delivered text sources can be found.
#### Daughter board
The *daughter_board* folder contains images and source code of the daughter board schema
#### Enclosure
The *enclosure* folder contains a 3d model and renders of the enclosure for navigator units

### Project page
TBD, a project page for navsys will be made

### Components
navsys system contains of several components, each of them stored in a separate repository:
* [navsys-backend](https://github.com/yedlosh/navsys-backend)
  + Backbone of the whole system, Express.JS based server acting as an intermediary for all the other components
* [navsys-navigator](https://github.com/yedlosh/navsys-navigator)
  + Navigation units powered by Raspberry Zero W, equipped with digital LED strips. Based on Express.JS as well, they are exposing a REST interface for accepting commands.
* [navsys-client-android](https://github.com/yedlosh/navsys-client-android)
  + The user facing component of this system, which provides interface for selecting desired destination, and collecting WiFi fingerprints for localization needs.
* [navsys-manager](https://github.com/yedlosh/navsys-manager)
  + Simple web application written in React, created for purpose of easy system administration.
