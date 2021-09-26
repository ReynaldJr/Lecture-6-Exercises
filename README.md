# Lecture-6-Exercises
4 exercises for lecture 6.

// Exercise 1: Odd or Even

    #include <iostream>
    using namespace std;

    int main() {

      cout << "A Program to Check if The Number is Odd or Even!\n\n"; // Outputs the title of the program.

      int num; // Declares the integer num. 

      cout << "Enter an integer: \n"; // Outputs 'Enter an integer' to guide the user what to input.
      cin >> num; // User enters the number


      if (num % 2 == 0) { // A formula to check if the number is even or not. 

        // Basically, a number is divided to 2. If the remainder is 0, the number is even. If not, the number is odd.

        cout << num << " is even.\n";  // Displays that the number is even.

      }

      else {

        cout << num << " is odd.\n"; // Displays that the number is odd.
      }

      cin.get();
      return 0;

    }


// Exercise 2: Number Checker

    #include <iostream>
    using namespace std;

    int main() {

      cout << "A Program to Check if The Number is Positive, Negative, or Zero!\n\n"; // Outputs the title of the program.

      double num;

      cout << "Enter a Number: \n"; // Outputs 'Enter a Number' to guide the user what to input.
      cin >> num; // User enters the number


      if (num < 0) { // Checks if the number is less than 0.

        cout << num << " is negative.\n"; // If number is less than 0, the program displays that the number is negative.

      }

      else if (num == 0) { // Checks if the number is equal to 0.

        cout << num << " is zero.\n"; // If number is equal to 0, the program displays that the number is zero.
      }

      else { // Checks if the number is greater than 0.

        cout << num << " is positive.\n"; // If number is greater than 0, the program displays that the number is positive.
      }

      cin.get();
      return 0;

    }
    
    
 
 
 
// Exercise 3: Profit or Loss

    #include <iostream>
    using namespace std;

    int main() {

      cout << "A Program to Calculate Profit or Loss\n\n"; // Outputs the title of the program.

      double purchase_price, sale_price;

      cout << "What is the purchase price of the item? \n"; // Outputs a question for purchase_price to guide the user what to input.
      cin >> purchase_price; // User enters the amount for sale_price

      cout << "What is the selling price of the item? \n"; // Outputs a question for sale_price to guide the user what to input.
      cin >> sale_price; // User enters the amount for sale_price.


      double result = sale_price - purchase_price; // A formula to calculate the result


      if (result < 0) { // If the result is less than 0, a loss incurred will be displayed.

        cout << "Loss Incurred = " << result;

      }


      else if (result == 0) { // If the result is equal to 0, a 'no profit nor loss' will be displayed.

        cout << "No Profit nor Loss.";

      }

      else { // If the result is greater than 0, a profit gained will be displayed.

        cout << "Profit Gained = " << result;

      }

      cin.get();
      return 0;

    }
    
    
    
    
    
    
// Exercise 4: Name that Shape

    #include <iostream>
    using namespace std;

    int main() {

      cout << "A Program to Check the Name of the Shape from the Number of Its Sides! \n\n"; // Outputs the title of the program.

      int side;

      cout << "Enter the number of sides for a shape (FROM 3-10 ONLY): \n";  // Asks the user to enter the number of sides for a shape.
      cin >> side; // User inputs number of sides.


      // Note: The output is written like this because the instructions said to report the appropriate name as part of a meaningful message.

      if (side < 3) { 

        cout << "The number of sides is too low! What are you doing? I told you to input a number from 3-10 only. \n"; // This statement prints if the user inputs a number less than 3.

      }

      else if (side == 3) { 

        cout << "Love is made up of three main qualities: \n" << "1. Intimacy \n" << "2. Commitment \n" << "3. Intimacy \n\n" <<
          "Take away any of the three, and the TRIANGLE will come apart. \n\n" << "So, please maintain the TRIANGLE by keeping our love whole. \n"; // This statement prints if the user inputs a number 3.

      }

      else if (side == 4) { 

        cout << "What makes QUADRILATERAL-shaped books special is that they let you travel without having to move your feet.\n";  // This statement prints if the user inputs a number 4.

      }

      else if (side == 5) {
        cout << "A PENTAGON-shaped diamond isn't born polished and gleaming. It used to be nothing exceptional, but with pressure and time, it transforms into something spectacular.\n"; // This statement prints if the user inputs a number 5.

      }

      else if (side == 6) {

        cout << "You're like a snowflake, prettier than any other HEXAGON in the sky. \n"; // This statement prints if the user inputs a number 6.
      }

      else if (side == 7) {

        cout << "Words are similar to HEPTAGON-shaped arrows. Once you let it go, you can't get them back. That's why you should use your words wisely.  \n"; // This statement prints if the user inputs a number 7.

      }

      else if (side == 8) {

        cout << "It's amusing that an OCTAGON-shaped stop sign is a guideline that teaches you that continuing in the same route will not lead you to anywhere new. \n"; // This statement prints if the user inputs a number 8.

      }

      else if (side == 9) {

        cout << "You are a person who keeps me secure and safe, a person who keeps my demons and fears away. You are like my personal NONAGON-shaped dreamcatcher.\n"; // This statement prints if the user inputs a number 9.


      }
      else if (side == 10) {

        cout << "Our fate is not in the hands of DECAGON-shaped stars, but in our own hands.\n"; // This statement prints if the user inputs a number 10.


      }
      else {

        cout << "The number of sides is too high! What are you doing? I told you to input a number from 3-10 only. \n"; // This statement prints if the user inputs a number greater than 10.

      }
      cin.get();
      return 0;

    }
