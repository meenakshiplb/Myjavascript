# Myjavascript
java script in in free code 
var myStr= “Firstline\n\\\Secondline\\\\rThirdline” ;


===============================

// Setup
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here
  
  if(myObj.hasOwnProperty(checkProp)){
    // double quote not needed for checkprop-----------important
    return myObj[checkProp];
  }
  
  else{return "Not Found";}

}

// Test your code by modifying these values
checkObj("pet");

