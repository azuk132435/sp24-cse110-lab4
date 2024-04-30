1. The bug was that result was doing string concatenation from + when what we wanted was to add 2 numbers.
2. To fix this bug I would simply convert the inputs to numbers using the Number() function. Since both num1 and num2
   will be assigned to a number the + will correctly just add the numbers.
