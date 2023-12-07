# Step 6: Combining Variables and Text

## Now that you know the basics of getting the console to print text and how to create variables, we can combine those concepts.

1. If you modify your Console.WriteLine function to say something along the lines of "The sum of x and y is x + y" and run the program, it won't print the sum of the values like it did previously. This is because you haven't specified that you want to use the variables so the console will only print the text.
2. To get both text and variables to print, you need to change two things in your WriteLine function.
  * First, type a "$" before the first quotation mark. ($"");
  * Next, use curly brackets around the variables that you want to add together. ($"The sum... {x + y}");
3. Now, with these changes, you can run your program. It should print both the text that you have and the sum of the values of your variables.
  * " The sum of x and y is 3"
