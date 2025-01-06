# cmsc131-description
Due to the University of Maryland's academic policies, I cannot make my projects for CMSC131 (Object Oriented Programming I) public.
Thus, I have described my work for these projects below.
If you are an employer, I can share my private code repository with you. Just email me at tanner.george@outlook.com

# Project 1: Java Basics & Conditionals
- Area.java: Computes the area of a triangle
- Divisible.java: Determines if two numbers are divisible
- ColorGenerator.java: Computes a CSS color from user input

# Project 2: Java Loops
- Convert.java: Converts a positive decimal number to octal
- ThrowDie.java: Simulates throwing a die a given number of times with a provided seed
- Access.java: Checks if users enter correct credentials for a system

# Project 3: Drawing App
- DrawingApp.java
  - isValidColor: Checks if a given color is valid
  - getRandomColor: Generates a random color
  -   getRectangle: Returns a string with a rectangle of specified dimensions
  -   getHorizontalBars: Returns a string with the number of horizontal bars. Each bar is of equal length and has a different color.
  -   getFlag: Returns a string with a triangle on the left side and horizontal bars on the right side
  -   getVerticalBars: Returns a strign with a number of equally-large vertical bars that correspond to different colors.

# Project 4: Passport
- Passport.java: Models a passport with the following methods
  - addStamp: Adds a new stamp to the passport
  - getStamps: Returns the stamps on the passport
  - getSeparator: Returns the current separator
  - setSeparator: Checks if a new separator is valid and changes the current one accordingly
  - equals: Checks if two Passport objects have the same data
  - compareTo: Compares Passports by owner name
  - getNumberOfPassportObjects: Returns the number of passport objects
  - normalize: Returns a new Passport object with all values in uppercase if the provided parameter is true, lowercase if false

# Project 5: Array Utilities
- Utilities.java
  - getArrayString: Returns a string where each array entry is separated by a specified separator
  - getInstances: The number of array values wihtin a range
  - filter: Returns a new array with values between a lower and upper limit
  - rotate: Rotates the array by the specified number of positions. If the boolean parameter is true, rotate left; else, rotate right
  - getArrayStringsLongerThan: Returns a new StringBuffer array with copies of StringBuffer objects in an array parameter with a specified mimimum length

# Project 6: Photo Manager
- Photo.java
  - toString: Returns a string with pertinent data
  - getPhotoSource: Returns the photo source
  - getWidth: Returns the photo width
  - getHeight: Returns the photo height
  - getDate: Returns the photo date
  - addComments: If the comment is valid, add it to a StringBuffer holding all comments
  - compareTo: Compare two Photo objects by date
- PhotoManager.java
  - addPhoto: Creates a new Photo object with the specified data
  - toString: Returns a string of all photos, each on a new line
  - findPhoto: Returns the index in an ArrayList with a Photo that has a specified photoSource
  - addComment: Add a comment to the Photo that has the given photoSource
  - getComments: Return the comments from a Photo with the provided photoSource
  - removePhoto: Remove the Photo with a given photoSource
  - loadPhotos: Load Photo objects to an ArrayList with data from a text file
  - sortPhotosByDate: Sorts photos by date
  - createHTMLPage: Creates an HTML file with all photos

# Project 7: Diagram System
