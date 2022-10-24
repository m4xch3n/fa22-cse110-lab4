1. The output from line 12 would be 3, because the for loop increments 3 times due to the 3 objects in the array passed when the function is called. Because each variable is var, it continues to persist outside the for loop and can be accessed and returned.
2. The output from line 13 would be 150 because the last iteration of the loop is going to set discountedPrice equal to the last element in the array, 300, multiplied by 1 minues the discount, which is 0.5, meaning discountedPrice equal to 150 before the loop exits. 
3. The output from line 14 would be 150 because the Math.round function simply rounds the inputted number to the nearest integer, so by multiplying, rounding, and then divinding the code seems to be trying to find the dollar/cents value, but since 150, the valeu of discounted Price at the last iteration, is alredy a whole number no changes are made to the value.
4. The function will return an array of integers, each of them with the applied discount set by the user when they called the function. In this particular case, the function will return an array of 3 integers, each on being [50, 100, 150].
5. The function will throw an error because the code attempts to access the variable i, but since it has been cast as a let type, it's scope is only within the for loop it was declared in, making the call to it outside of the loop invalid.
6. Again, the function will return an error because the code is trying to access discountedPrice outside of the block it was declared in.
7. The function will return 150, because even though finalPrice is a let variable, which means it only exists in the blockl it was declared in, the console.log is within the same block as well, making finalPrice a valid variable to call.
8. The function will return the same thing as iot returned for questiopn 4, an array of 3 integers in the order [50, 100, 150]. The only difference is that the variables are all let variables, but since the return statement is inside the function discounted was declared in, it will return the values with no errors.
9. The function will throw an error because i was declared in the for loop with a let declaration, meaning that outside of the scope of the for loop i will not be able to be called and the console.log call is outside of the for loop slope
10. The function will retrun 3, since the const variable is both within the scope of the console.log call and the value is initliazed at the size of the arrau inputted, which is 3
11. This function will return the same 3 integer array returned in questions 4 and 8 because even though the discounted array is constant, the function changes the values within the array, which is allowed. In addition to this, the mathematical logic is the same and so the output will be the same as the others.
12a. student.name
12b. student['Grad Year']
12c. student.greeting()
12d. student['Favorite Teacher'].name
12e. student.courseLoad[0]
13a. 32; This is 32 beacause when we add a string to a number, they concatenate instead of perform arithmatic
13b. 1; This is 1 because when we subtract because the subtraction operator casts the string back into a number and performs the arithmatic
13c. 3; javascript treats null as 0 in arithmatic so the answer is 3
13d. 3null; Javascript sees a string and a plus so it does string concatenation
13e. 4; true gets turned into 1 when doing arithmatic, making the answer 4
13f. 0; false gets turned into 0 doing arithmatic, and as stated before null is also 0 so we get 0 
13g. 3undefined; Because we start with a string and a plus sign, string concatenation happens
13h. NaN; undefined causes the compiler to output NaN no matter what operation is performed
14a. true; Javascript casts the string 2 into a number and then outputs true beacsue 2 is greater than 1
14b. false; Because they are both strings, it goes by dictionary comparision and 2 is greater than 1 so it's false
14c. true; because of the ==, it's not a strict checlk and since 2 and '2' are the same except for type, it returns true.
14d. false; because of the ===, it IS a strict checkl including type, so since they are different ypes it returns false
14e. false; Even though it's not a strict check, true is equal to 1 and not 2, therefore it still returns false
14f. true; when we cast 2 into a boolean, beacuse it's not 0 or null or anything like that, it becomes true and true is equal to true
15. The two equal signs check to see if the two objects are a "sweet pair", that is whether they are equal to each other and nothing else. This means a string '2' can be equal to the number 2. The three equal signs are a strict equality check, and would not allow '2' to be equal to 2 because one is a string and the other a number
17. The output given the parameters mentioned in the canvas querstion, the output would be an array with the values [2, 4, 6] inside. This function works by taking each element in the array passed and sending it through the function the user passes before putting it in a brand new array to return
19. This code outputs the numbers 1 and 4 instantaneously, and followed directly by 3 with no delay, and then one second later 2 is printed. 
