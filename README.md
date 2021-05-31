# swift-FilterbyDigitLength

<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Swift Study</h3>
  <p align="center">
    Project to study Swift 5.4
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
 
  
     Create a function that filters out an array to include numbers that only have a certain number of digits.
     
     Examples:
     filterDigitLength([88, 232, 4, 9721, 555], 3) ➞ [232, 555]
     // Include only numbers with 3 digits.
     filterDigitLength([2, 7, 8, 9, 1012], 1) ➞ [2, 7, 8, 9]
     // Include only numbers with 1 digit.
     filterDigitLength([32, 88, 74, 91, 300, 4050], 1) ➞ []
     // No numbers with only 1 digit exist => return empty array.
     filterDigitLength([5, 6, 8, 9], 1) ➞ [5, 6, 8, 9]
     // All numbers in the array have 1 digit only => return original array.
     
     Notes:
     If no numbers of the specified digit length exist, return an empty array.
     If all numbers in the array have the specified digit length, return the original array.
     The sub-array returned should have the same relative order as the original array.

     Excercise from: https://edabit.com/challenges/swift


<!-- GETTING STARTED -->
## Getting Started

Open the file FilterbyDigitLength.xcodeproj 

### Prerequisites

* Xcode 12.4
* Use iPhone 12 mini as simulator 

<!-- CONTACT -->
## Contact

Daniel Washington Ignacio - danielvertigo@hotmail.com

Click to access my [LinkedIn](https://www.linkedin.com/in/daniel-washington-ignacio-ab439b164/)
