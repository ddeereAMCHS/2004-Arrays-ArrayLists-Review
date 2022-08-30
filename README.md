# Arrays & ArrayLists Review

## Due: Thur 9/1 at 11:59 PM

- Create a program called `ArraysReview.java`
- Prompt the user for a filename
- Read in all the values and store them in both an array and an ArrayList
- Do the following actions for the array and then the ArrayList: (do not just do the actions on one and then copy the values to the other)
  - Remove the element with value 19 if it exists
    - If it exists, print "Element with value 19 removed" and shift any subsequent elements to the left
    - If it does not exist, print "No element with value 19 found"
  - Remove the element with value 7 if it exists
    - If it exists, print "Element with value 7 removed" and shift any subsequent elements to the left
    - If it does not exist, print "No element with value 7 found"
  - Set the element at index 3 to be 9
  - Insert an element with value 12 at index 5 and shift any subsequent elements to the right
  - Print all the values

***Example Input:***\
input.txt\
***Example Contents of input.txt***\
3\
14\
18\
5\
54\
16\
19\
34\
26\
17\
4\
22\
31\
45\
99\
***Example Output:***\
Element with value 19 removed\
No element with value 7 found\
[3, 14, 18, 9, 54, 12, 16, 34, 26, 17, 4, 22, 31, 45, 99]\
Element with value 19 removed\
No element with value 7 found\
[3, 14, 18, 9, 54, 12, 16, 34, 26, 17, 4, 22, 31, 45, 99]
