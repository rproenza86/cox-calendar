# Proof of concept for Cox

## Calendar appointments
This web app allow an user to view a list of available appointment times peer day and to select one. 
The appointment is saved in the database.

Application features:
1.            List of hour long slots from 9am to 5pm corresponding to each day.
2.            When one time slot is clicked, pop up a modal which asks for name and phone number.
3.            When the name and phone number is submitted, the time slot selected should change to red, indicating the time slot is no longer available.
4.            If the red time slot is clicked on again, the modal will pop up with the name and phone number for that appointment pre-populated. Users will be able to edit the name and phone number to change the user for the appointment.

## Autor:
Ing. Raul Rodriguez Proenza

#### Technologies, Techniques and tools:
* FronEnd: Polymer, HTML5 and CSS3, ES6
* BackEnd: Firebase(Database, Authentication, Hosting)
* Version control: GitHub

The PRPL pattern, in a nutshell:

* **Push** components required for the initial route
* **Render** initial route ASAP
* **Pre-cache** components for remaining routes
* **Lazy-load** and progressively upgrade next routes on-demand

### Setup

##### Prerequisites. Clone the repository and run this commands

    npm install -g polymer-cli
    npm install
    bower install
    polymer serve --open