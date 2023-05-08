Download Link: https://assignmentchef.com/product/solved-solvedproject-4-a-domino-class
<br>
The classic domino set is played with 28 dominoes. Each domino is divided into halves, each half has either a number of pips (black spots) ranging from 1 to 6 or is blank. The half with the greatest number of pips is called the major suit, and the other half is the minor suit. A domino whose minor suit has no pips is referred to as a blank. A domino that has identical halves is called a double. Additionally, the weight of a domino is the total number of pips in both halves. Moreover, a domino is ranked according to its major and minor suits. A domino is ranked higher than another domino when its major suit is greater than the other domino’s major suit or when it has the same major suit as the other but its minor suit is greater than the minor suit of the other . Finally, a domino is usually named by specifying the minor suit first and then the major suit, for example, a domino whose minor suit is 3 and major suit is 5 is named as 3 – 5. The following table illustrates the major, minor and weight of several domino s as wells as whether they are a double and/or a blank.

Major Minor Blank Double Weight Name2 0 Yes No 2 0 – 25 3 No No 8 3 – 54 4 No Yes 8 4 – 45 2 No No 7 2 – 50 0 Yes Yes 0 0 – 0

The dominos in the previous example can be sorted by their rank (from highest to lowest rank) as follows: 3 – 5, 2 – 5, 4 – 4, 0 – 2 and 0 – 0. Note that the 2 – 5 domino has a higher rank than the domino 4 – 4, even though the latter has a higher weight.

You have been given a skeleton for a class called Domino (Domino.java) which represents a domino in a standard domino set. For the first part of the assignment, you will fill out the code so that the Domino class works as required. Each Domino object has two integer attributes – minor and major. Both major and the minor are integers between 0 and 6 and the major is always greater than or equal to the minor.

The Domino class should allow any domino object in a standard domino set to be created, but it should NOT allow creating a domino with any other numbers for the major or the minor. If someone tries to create a domino with a major suit of 7 and a minor suit of 8, for example, the program should default to the blank domino (minor 0 and major 0). You will need to complete the declaration of each method properly and fill out each method as described in the comments at the top of the method.

As you are writing the code, use the DominoTester program to test your class to make sure it is working correctly. When every method of your Domino class is properly implemented with no errors, the output will look something like this:

Major Suit of Domino 1 is correct!Minor Suit of Domino 1 is correct!Major Suit of Domino 2 is correct!Minor Suit of Domino 2 is correct!Domino 1: 0 – 6 toString is working correctly for domino 1Domino 2: 3 – 3 toString is working correctly for domino 2isBlank is working correctly for domino 1isDouble is working correctly for domino 2getWeight is working correctly for domino 1getWeight is working correctly for domino 2Randomly Generated domino: 2 – 5Invalid domino defaulted to: 0 – 0

Additionally, write a client class called RandomDomino.java that randomly generates 20 Domino objects (you can just use the default constructor) and prints them out, one by one. At the end of printing out the 20 domino s, your program should print the heaviest domino with the highest rank, the lightest domino with the lowest rank, the number of blanks and the number of doubles among the generated dominos.Example 1:20 randomly generated dominos:1 – 30 – 52 – 30 – 13 – 61 – 50 – 12 – 41 – 20 – 40 – 63 – 50 – 41 – 60 – 11 – 30 – 32 – 60 – 41 – 4Heaviest domino with higher rank: 3 – 6Lightest domino with lowest rank: 0 – 1Number of doubles:0 Number of blanks:9

Example 2:20 randomly generated dominos:2 – 53 – 41 – 22 – 31 – 63 – 51 – 50 – 62 – 41 – 60 – 41 – 43 – 30 – 51 – 24 – 40 – 61 – 32 – 21 – 4

Heaviest domino with higher rank: 3 – 5Lightest domino with lowest rank: 1 – 2Number of doubles:3 Number of blanks:4

Deliverables• Domino.java• RandomDomino.java