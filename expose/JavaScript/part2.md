# A Little More of a Challenge...

1.The code will log the value 'i', which here would be 3. This is because in the for loop i is scoped to the entire function rather than just the loop block, after the loop terminates it will be at 3.

2.This will log the value discountedPrice which is 150. This is because the value of discountedPrice is being reassigned in the loop giong through until we get to 300 as the final element, in which that is halved resulting in 150.

3.This will log the value 150 because similar to before since discounted.push(finalPrice) will be reupdated in the loop for each iteration the revelevant log will be for the 300 price which after discount it 150, returning the same as the previous question.

4.It will return the array [50,100,150] as the discounted array is being updated at every iteration of the loop for the 3 presented prices prior to the discount. It will not log it tho so nothing is actually displayed out.

5.At line 12 this will result in an error because i is not defined outside of the loop. The console log it calling for i outside of the loop which is out of scope the creation of i being "let i = 0" in the for loop.

6.At line 13 this will also result in an error because discoutedPrice is declared using "let" which means it is only acceptable inside the loop. So in order to log its value you need to log it inside the loop not outside.

7.This will similarly as before log 150. This is because it was declared wihtout using let unlike the rest of the variables. It will take the latest value which was the 300 with a 0.5 discount resulting in 150.

8.This will return the array [50,100,150]. This is because the let discounted = []; is at the beginning of the function. This array will be accessible throughout the function. It will go through and be updated at each loop iteration correctly updating the half prices being [50,100,150].

9.This will result in a referenceError because the variable is being declared using let within the for loops cope. The attempt to log "i" is outside of the scope.

10.This would log 3 because the prices array has 3 elements which means the length would be 3, and we are logging the length.

11.This function will return an array containing the discounted prices [50, 100, 150]. This is because for each item in the prices list the discount is applied and then pushed onto the discounted array. Ultimately returning the final array beinga ll 3 of the prices with the 0.5 discount.

12. A. student.name B.student['Grad Year'] C.student.greeting(); D.student['Favorite Teacher'].name E.student.courseLoad[0]

13.
A. This will output '32' because the + operator when done on strings concatenates. So it concats the 2 on the 3 resulting in '32' <br>
B. This will output 1 because the - operator, JS converts the operands to numbers. This makes the '3' become a 3 and then 2 is subtracted resulting in 1.<br>
C. This will result in 3 because null is treated as a 0 in numerical context. 3 + 0 = 3.<br>
D. This will output '3null' because similar to A it will concat strings together so it takes the 3 and concats the letters null onto it resulting in teh string '3null'.<br>
E. This will ouput 4. This is because true in JS is converted to a 1 in numerical context. 1 + 3 = 4.<br>
F. This will output 0. This is because in JS false and null when in numerical context both becomes 0. 0 + 0 = 0.<br>
G. This will output '3undefined' because once again the + will concat strings together adding the undefined to the 3.<br>
H. This will output NaN because when trying to run an arithmetic operation with undefined JS converts undefed to NaN. Subtracting NaN from 3 results in NaN.<br>

14.
A.This would output true. This is because when comparing 2 types here the string will be converted to a number and 2 is > 1.<br>
B.This would result in false. This is because when comparing 2 strings JS compares them character by character left to right. Since '2' is compared to '1' the result is false as 2 is > 1.<br>
C.This would result in true. The ==  allows for type coercion. This would make the string '2' convert to the number 2 and 2 == 2 evalutes to True.<br>
D.This would result in false. This would be false. This is because the === operator is a strict equality comparison without type coercion so since they are different types it evaultes to false.<br>
E.This would result in false. This would result in false because when comparing a boolean to a non-boolean value the boolean is converted to a number. So here true becomes a 1, and 1 == 2 evaluates to false.<br>
F.This would result in true. This is because Boolean(of any non-zero number) is considered true. This results in a direct comparison between 2 booleans being true === true which is true.<br>

15.So == is the equality operator and it checks for equality after doing type coercion if the operads are different types. Effectively JS tries to convert them to the same type before comparison allowing things like 1 == '1' to be true. === is the stric equality operator that checks for equality without perform the coerction. So with the samne example 1 === '1' this would be false as it takes a strict comparison of the two with no type changing.

16. [file 16](part2-question16.js)

17.This will return the array [2,4,6]. modifyArray initailzes newArr as an empty array. It then enters a loop from i = 0 to 2. In each iteration doSomething is called in which the current elemnt of the array is being multipled by 2 having 1,2,3 become 2,4,6. They are then pushed onto the newArr and this is returned.

18. [file 18](part2-question18.js)

19. The output is 1 4 3 2 each on seperate lines. This is due to first the 1 is logged. Then there is a 1 second delay to log the 2. During this time log(3) is added into a queue. Then the console logs 4. After this is done the call stack is empty which allows JS to pick the first item from the queue being log 3. Lastly after that 1 second delay 2 is logged last.

