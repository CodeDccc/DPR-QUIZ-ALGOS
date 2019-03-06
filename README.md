# DPR-QUIZ-ALGOS
Algorithm Quiz 1
 
<h4>Please answer the following questions by forking this project. Respond within the README file by editing it. Then submit your Github URL on Canvas</h4>
<ol>
 <li>What does sheevpalpatine.java do? You can copy the code from above and use a browser ide here... https://www.compilejava.net/</li>
  <li>Submit a binary search example by adding a file to this project after forking it. Be sure to explain how the example functions using comments or in this README.</li>
  <li>Is a selection sort or a bubble sort faster?</li>
 </ol>

--- Sheevpalpatine.java is a program that can tell if a word is a palindrome - so it take a word and checks if the word is spelt the same     way back to front as it is front to back; i.e. level is a polindrome.

--- The binary search code is designed to search for a number within a given array. It works by finding the middle number in the array and comparing it to the number your searching for. If they match, then the program ends, if they don't match, then the array is cut in half- from the mid point to the end and from the mid point to the beginning. The program will then check if the searched number lies above the mid point or below, after establishing this, the program then compare the number we seek to the mid point of this 'halved section'. The program will continue to loop through this halving process until the number is found or we run out of numbers - at which point it will be deemed the search number is not in the array.

--- Bubble sort algorithm sorts data by comparing 2 numbers at a time, if the second number is less than the first number, then a swap is made, otherwise no swapping and this continues until all the data is sorted; i.e. {5, 3, 4 9} 5 and 3 will be compared and swapped = {3,5,4,9}; then 5 and 4 will be compared and swapped = {3,4,5,9}; then 5 and 9 will be comapred, but they won't swap because 5 is less in value than 9. --- Selection sort works by comparing all the elements from the first to the last and then it will swap any element which does not appear before a larger element and it will do this until all the elements are sorted; i.e. {7,5,2,1}, after scanning the program will swap 7 with 1 = {1,5,2,7}; then after scanning again the program will swap 5 with 2 = {1,2,5,7}.

--- Selection sort is faster then bubble sort.
