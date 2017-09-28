# First-Build-Repository

//Open Alexa

var Alexa = require("alexa-sdk");

//Recieve message "Hello Alexa, this is Melissa or Alma"





//Respond with "Hello Melissa/Alma"

var Handlers ={
  "HelloIntent": function () {
    this.response.speak("Hello, Melissa"); 
    this.emit(':responseReady');
};


//Open Function to give local weather for the day





//Open function to give calendar appointments for the day

//Go to either calendar for Melissa or Alma 

//Respond with appointments on calendar 

//End by saying "Enjoy your day"
