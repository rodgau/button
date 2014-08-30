## Welcome to button: Event-based ##


This is an introductory [electric imp](http://electricimp.com) project.
# Overview #

This project builds on 'button' by introducing an imp event-based model to detect a button press. 

### Device-side Functionality  ###
Rather than a looping poll, an event handler manages things. When a button is either pressed (or released) this gets detected and fires the handler function. In turn, the handler confirms the button state then sets the LED accordingly.

 It then updates the server.log with its either *pressed* or *not pressed* status.
### Agent-side Functionality  ###
None.
