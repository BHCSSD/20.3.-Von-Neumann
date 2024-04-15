# 20.3.-Von-Neumann

In this assignment, you will look into how a Central Processing Unit (CPU) works. The main function of this is to introduce you to how the CPU gets information in, decodes it, and then runs that information. When you are done your goal is to know that the CPU is more than a little square chip that lives on the motherboard.

## Part 1 Naming, defining, and drawing part of the CPU
- You can use this link to find the basic information for Part 1 and some of Part 2 of this project.
  -   https://youtu.be/C0Pch0zpsT4?si=6de9eOCT7pOJHNPE   Use the image form 2:13 in this video for your drawing 
 
These are basic components of the Central Processing Unit (CPU), please draw out the CPU and provide clear and concise definitions for each
  - The Register
    - Program counter
    - Memory address register,  (MAR)
    - Memory Data Register (MDR)
    - Aculimator
  - control unit, (CU)
  - Arithmetic Logic Unit (ALU),
  - Cache

```
  let descriptX = 100 // sets xfor where definition shows up
  let descriptY = 10 // sets y for where definition shows up


function setup() {
  createCanvas(800, 800);

  // rectMode(CENTER)
  textAlign(CENTER)
}

function draw() {

  background(255);

  // block 1 copy this code, edit the numbers to make other blocks
  rect(50, 50, 100, 100); //input box
  
  if (mouseX < 150 && mouseX > 50 && mouseY < 150 *& mouseY > 50 ) {
    text("input device", mouseX, mouseY) //name of the block
    text("information provided by user", descriptX, descriptY) // definition of 
  }//end if

// start your next block here. 


  
  }// end draw 


// if you click this it will tell you where your mouse is
function mousePressed(){
  print(`X:${mouseX}`) 
  print("y:"+ mouseY)
}
```
  - Clock
  - Random access memory (RAM) 



