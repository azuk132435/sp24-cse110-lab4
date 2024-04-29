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
