<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# LUMOS — CURRENT POYYO? 🎯

## Basic Details

### Team Name
**SeveralSnape**

### Team Members
* **Team Lead:** Roshan Robin — ASIET, Kalady
* **Member:** Jayalakshmy Jayakrishnan — ASIET, Kalady

---

### Project Description
Our project finds out whether an average KTU student is able to study outside in the moonlight when KSEB cuts the power. We take time, location, moon cycle, and weather conditions to see if we should depend on nature before on the state electricity board.

### The Problem (that doesn't exist)
Have you ever came home late from your college with a ton of assignments and record to complete only to find theres no electricity at home. Well, Before you call KSEB to complain you should remember "Where there is a will there is a way". Maybe KSEB is not the issue. Maybe we are being too quick to call KSEB before thinking of other options.

### The Solution (that nobody asked for)
We have made Lumos especially for those poor KTU students with no inverter at home. We take the moon cycle and weather conditions to see if there is enough moonlight at the user's location for them to do their work on the terrace. We also measure the wind speed to ensure that the user knows how breezy the terrace is. This is to ensure that our average KTU student is not affected by the KSEB power cuts.

---

## Technical Details

### Technologies / Components Used

* **HTML5** — Application structure and interface
* **CSS3** — UI styling, animations, and responsive layout
* **JavaScript** — Application logic, API communication, and decision-making
* **SunCalc** — Astronomical calculations including moon position, altitude, and phase
* **Open-Meteo** — Weather and environmental data
* **Browser Geolocation API** — Obtaining the user's location
* **Netlify** — Static web hosting and deployment

---

## Software Implementation

Lumos is implemented as a **standalone client-side web application**. There is no dedicated backend server.

### Pipeline Architecture

```text
User
  │
  ▼
Browser Location + Current Time
  │
  ├──────────────► SunCalc
  │                  │
  │                  ├── Moon Phase
  │                  ├── Moon Altitude
  │                  └── Moon Position
  │
  └──────────────► Open-Meteo
                     │
                     ├── Cloud Coverage
                     └── Wind Speed
                             │
                             ▼
                     Condition Analysis
                             │
                             ▼
                    Study Feasibility
                             │
                             ▼
                  ┌────────────────────┐
                  │   LUMOS DECISION   │
                  ├────────────────────┤
                  │ STUDY OUTSIDE      │
                  │ WAIT               │
                  │ CALL KSEB          │
                  └────────────────────┘
```
# Run
Standalone HTML file just download and open.

### Project Documentation
For Software:

# Screenshots 
Initial Screen
<img width="1078" height="693" alt="image" src="https://github.com/user-attachments/assets/30fdf846-bb9d-4f89-b3f2-b09f87504224" />

*The "Current Poyii?" button asks permission to use location and time data from the browser*

Output
<img width="997" height="671" alt="image" src="https://github.com/user-attachments/assets/7543c0a8-7c64-4d39-ba45-09ea01b271d2" />

*The output shows whether or not the user can study on the terrace with enough light and wind and if not the option to call KSEB.*

Moon-Eater
<img width="732" height="646" alt="image" src="https://github.com/user-attachments/assets/c8f24816-9ccc-4a03-a834-ccb131c920fa" />

*While we deliberate and procrastinate on calling the KSEB or just plain waiting for the power to come back play a little mini-game*

# Diagrams
<img width="1647" height="944" alt="image (2)" src="https://github.com/user-attachments/assets/34a91165-e24d-4441-91c8-1c072f03225a" />

*Uses Location and time to find out moon cycle and weather conditions, and then use them to calculate whether ther is enough light or lux value for the student to study in. Also provides the mini-game and UI features *

### Project Demo
# Video
[https://drive.google.com/file/d/1J2PPIXWqaeCzpGiCuqkfquL5QnN8s-xd/view?usp=sharing](https://drive.google.com/file/d/1G2VgwioMmXazCV7ZT41arcEyauyweZDG/view?usp=sharing)
*The video shows the initial fetch of the location and time from the user and then uses them to calculate the lux values to find out whether the student can study or call KSEB*

# Additional Demos
*Deployed Link:* https://stalwart-gaufre-89adb2.netlify.app

## Team Contributions
- Jayalakshmy Jayakrishnan: Final product and UI
- Roshan Robin: Initial Work and Documentation

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)





