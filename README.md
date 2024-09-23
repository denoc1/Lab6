# Lab6 - Practice with Static Methods

Be sure to include your standard comments at the top of your program.

Write a class with the following five **static** methods.  Notice, the method headers have been included for you!


    // given two integers x and y, returns their average.
     public static double average (int x, int y)
     {...}

     // given two integners, x and y, return the difference x - y  (notice, order matters!)
     public static int difference (int x, int y)
     {...}

     //given an integer x, return its suare, x * x
     public static int square (int x)
     {...}

     //given two points (x1, y1) and (x2, y2), return 
     //the slope of the line through them.  You may assume x1 is not equal to x2
     public static double slope (int x1, int y1, int x2, int y2)
     {...}

     // given two points (x1, y1) and (x2, y2), return the distance between them.  
     // You MUST CALL  the methods difference and square above.
     //  In addition, you CANNOT use subtraction nor multiplication in this method!
     //  recall:  distance = \sqrt((x1 - x2)^2 + (y1 - y2)^2)
     public static double distance(int x1, int y1, int x2, int y2)
     {...}


Write your main() method so that your program has an output similar to:
      
        The average of 8 and 9 is 8.5
        The slope of the line through (8, 9) and (2, 4) is 0.8333333333333334
        The distance between (8, 9) and (2, 4) is 7.810249675906654



Notice the formatting of the points on the coordinate plane (x, y)

Your code must work on different input values.  For example, I might change the input values in your code.  Be sure it works for any input values, not just the ones in the example above (except for those that give arithmetic exceptions, of course!).
