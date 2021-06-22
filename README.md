-You can not have repeating numbers in a column
  -loop through each array of each element at i to make sure there are no repeating numbers
  A[0] compare to B[0] compare to C[0], etc
  -Generate a new array for columns [A[0], B[0], C[0], D[0]] - then analze that array with a for loop?
  
-You can not have repeating numbers in a row
  -for loop - loop through the array and check to make there is no duplication of numbers

-You can not have repeating numbers in a 3x3 box
  - Create an array A[0], B[0], C[0], A[1], B[1], C[1], A[2], B[2], C[2] - then analyze that array with a for loop?
  - use a for loop to create the new array


let firstRow = [5, 3, B, B, 7, B, B, B, B]
 firstRow.forEach(function(element) {
   if (firstRow.includes(element)
 }

function checkValidRowInput(userInput[where they clicked]) {
  for (let i=0; i <= firstRow.length; i++) {
    if (firstRow[i] != userInput)) {
      firstRow[where they clicked] = userInput;
    } else {
      alert('Not Valid Input');
      return false; 
    }
  }
  
}


A [5, 3, B, B, 7, B, B, B, B]
B [6, B, B, 1, 9, 5, B, B, B]
C [5, 3, B, B, 7, B, B, B, B]
D [6, B, B, 1, 9, 5, B, B, B]
E [5, 3, B, B, 7, B, B, B, B]
F [6, B, B, 1, 9, 5, B, B, B]
G [5, 3, B, B, 7, B, B, B, B]
H [6, B, B, 1, 9, 5, B, B, B]
I [5, 3, B, B, 7, B, B, B, B]


function Sukoku() {
  this.rowA = [];
  this.rowB = [];
  this.rowC = [];
  this.rowD = [];
  this.rowE = [];
  this.rowF = [];
  this.rowG = [];
  this.rowH = [];
  this.rowI = [];
  this.rowJ = [];
}