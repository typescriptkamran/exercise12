# exercise12
This TypeScript code demonstrates the use of an array, a loop, and string interpolation to print personalized messages for each name in the array. Let's break down the code step-by-step:

1. `let names: string[] = ['Muhammad', 'Ali', 'Javaid', 'Ahmed'];`
   - This line declares a variable `names` and assigns an array of strings to it. The array contains four names: 'Muhammad', 'Ali', 'Javaid', and 'Ahmed'. The type annotation `: string[]` indicates that this variable can only hold an array of strings.

2. `for (let name of names) { ... }`
   - This is a `for...of` loop. It iterates over each element (in this case, names) of the array `names`.

3. `console.log(`Good morning ${name}, I hope you are having a fantastic day!`)`
   - Inside the loop, this line uses string interpolation (backticks ``) to create a personalized message for each name in the array. The `${name}` part of the string is a placeholder that will be replaced by the current element (name) of the array during each iteration.

4. During the loop execution:
   - In the first iteration, `name` will be 'Muhammad', so the message will be: "Good morning Muhammad, I hope you are having a fantastic day!"
   - In the second iteration, `name` will be 'Ali', so the message will be: "Good morning Ali, I hope you are having a fantastic day!"
   - In the third iteration, `name` will be 'Javaid', so the message will be: "Good morning Javaid, I hope you are having a fantastic day!"
   - In the fourth iteration, `name` will be 'Ahmed', so the message will be: "Good morning Ahmed, I hope you are having a fantastic day!"

Overall, this code prints a personalized "Good morning" message for each friend's name present in the `names` array.
