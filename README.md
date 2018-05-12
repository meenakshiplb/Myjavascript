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

==================================================
important array mutiplication----------

function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  for (var i=0; i < arr.length; i++) {
  for (var j=0; j < arr[i].length; j++) {
    product*=(arr[i][j]);
  }
}
  // Only change code above this line
  return product;
}

// Modify values below to test your code
multiplyAll([[8,2],[3,4],[5,6,7]]);


