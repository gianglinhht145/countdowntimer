# countdowntimer
This countdown timer is like an alarm that will give the user options to set time and when the time is over, it will nofify the user. It also displays current time.
The project was built with basic Python libraries such as: time, playsound, tkinter
Step 1: import required module
Step 2: create a display window
  Tk() initializes tkinter to create the window
  geometry() set the width and height of the window
  resizable(0,0) prohibit users to resize the window
  title() used to set the title of display window
  bg used to set the color of background
  Label() widget used to display one or more than one line of text that users can’t modify
  root is the name of our window
  text which we display on the label
  font in which the text is written
  pack organizes widget in block
Step 3: create current time
  strftime() method return the string representing the time in given format
  after() method used to give a delay of 1000 millisecond which is 1 sec
Step 4: create function to start timer
  sec is a string type variable that stores the seconds.
  mins is a string type variable that stores the minutes.
  hrs is a string type variable that stores the hours
  Entry() widget is used to create an input text field.
  textvariable used to retrieve text from specific variable to entry widget
  place() widgets place widgets in a specific position in the parent widget.
  times variable gets the hours value multiplied by 3600 (1 h = 3600 sec), mins value multiplied by 60 (1 min = 60 sec), and sec value.
  ‘//’ operator returns the result of the division in a whole integer value
  ‘%’ operator used to returns the remainder of the division
  While time is greater then -1 the countdown will run. When times value become 0 then the countdown stop and a sound play that indicate your time is up.
Step 5: create button
  Button() widget used to display a button on window
  bd sets the size of the border
  command calls the function when we click on button
  root.mainloop() is a method which executes when we want to run our program
