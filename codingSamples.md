# Java Coding Samples 

Various Java programs to illustrate various concepts from an old CS course at UTexas.edu.

*   A [Hello World!](javacode/codeSamples/HelloWorld.java) Java program.
    
*   [Calling Methods](javacode/codeSamples/CallingMethodsInSameClass.java). A sample of how to call methods in the same class.
    
*   [For loop](javacode/codeSamples/Factorial.java). A simple example of using for loops to calculate factorial. Uses the built in int data type so only good to 13!
    
*   [Enhanced for loop](javacode/codeSamples/EnhancedFor.java)
    
*   [Value Parameters](javacode/codeSamples/PrimitiveParameters.java): An example that shows the behavior of value parameters. In Java all parameters are passed by value. 
    
*   [String Example](javacode/codeSamples/StringExample.java). A few brief examples of String manipulations.
    
*   [BinaryConverter](javacode/codeSamples/BinaryConverter.java). A program with examples of various Java syntax that converts a base 10 int to base 2 String.
    
*   [PrimeEx](javacode/codeSamples/PrimeEx.java) A program with various approaches to determine if an int is prime or not. Used to demonstrate Java syntax. You need the [Stopwatch](javacode/utilities/Stopwatch.java) class, a non standard Java class, as well.
    
*   [Pointers as Value parameters](javacode/codeSamples/ObjectVarsAsParameters.java)
    
*   [Array Examples](javacode/codeSamples/ArrayExamples.java)
    
*   [2D array Example](javacode/codeSamples/FilterExample.java). A simplified version of filtering a picture represented by ints.
    
*   [2D array example](javacode/codeSamples/Life.java). Very simple version of the Conway's Game of Life.
    
*   [Getting input from Keyboard with Scanner class](javacode/codeSamples/ScannerAndKeyboard.java)
    
*   [Reading ints from file with Scanner class](javacode/codeSamples/ReadAndPrintScores.java)
    
*   [Writing ints to file](javacode/codeSamples/WriteToFile.java)
    
*   [Connecting to and reading from a web page.](javacode/codeSamples/URLExpSimple.java)
    
*   [Program to create ASCII frequency table from file and url.](javacode/codeSamples/FreqTableExampleOriginal.java) Demonstration of try / catch blocks. The CIA 2008 Factbook may be downloaded from [Project Gutenberg](http://www.gutenberg.org/cache/epub/29233/pg29233.txt).
    
*   [IntListVer1](javacode/codeSamples/IntListVer1.java) First version of the IntList class developed in class. Developing class to illustrate various class design and implementation issues in Java.
    
*   [IntListTesterVer1](javacode/codeSamples/IntListTesterVer1.java)
    
*   [IntListVer2](javacode/codeSamples/IntListVer2.java) Added default add method, equals method, and toString methods. Includes versions of toString using String concatenation and StringBuffer to illustarte performance differences.
    
*   [IntListTesterVer2](javacode/codeSamples/IntListTesterVer2.java)
    
*   [IntListVer3](javacode/codeSamples/IntListVer3.java). Added insert and remove methods.
    
*   [SortedIntList](javacode/codeSamples/SortedIntList.java). Inherits from InListVer3 to create a SortedIntList. Class is "broken" because random insertions still allowed.
    
*   [GenericList](javacode/codeSamples/GenericList.java). Altered the list to store anything, not just ints.
    
*   [Die](javacode/codeSamples/Die.java) class. A class that models a playing die.
    
*   [DemoClass](javacode/codeSamples/DemoClass.java): This illustrates some of the more confusing concepts in class syntax and mechanics such as constructors, static vs. instance methods, and method overloading. 
    
*   [Stopwatch class](javacode/utilities/Stopwatch.java). A class for measuring how long it takes for a program to run.
    
    *   [Documentation for Stopwatch class.](javacode/utilities/Stopwatch.html)
        
*   [Create a Set](javacode/codeSamples/CreateASet.java). A method that using polymorphism to create a set from an array.
    
*   [Recursion examples](javacode/codeSamples/RecursionExampleDirectory.java). Includes examples on finding space taken up by files in a directory including all files in all subdirectories, recursive factorial, recursive power, recursive Fibonacci numbers, and a simple knapsack problem.
    
*   [Eight Queens example](javacode/codeSamples/EightQueens.java). Code to find a a solution to an N queens problem. Note the queensAreSafe method has not been completed.
    
*   [Airlines example](javacode/codeSamples/AirlineProblem.java). Determine if airlines can be moved from airline to another based on network of airline partners. Here is a [sample input file](javacode/codeSamples/airlines.txt).
    
*   [Minesweeper](javacode/codeSamples/MineSweeper.java). Another example of recursion from the game minesweeper.
    
*   [GenericListVersion2](javacode/codeSamples/GenericListVersion2.java). Changed the GenericList class so that it implements the [Iterable](http://java.sun.com/javase/6/docs/api/java/lang/Iterable.html) interface in order to demonstrate how to implement an [iterator](http://java.sun.com/javase/6/docs/api/java/util/Iterator.html) using an inner class.
    
*   [GenericListVersion3](javacode/GenericList.java). Changed GenericList so it is generic based on Java generics syntax instead of relying on Object.
    
*   [ListNode](javacode/codeSamples/ListNode.java). A singly linked node class used to build linked lists
    
*   [IList](javacode/LinkedList/IList.java). A simple list interface
    
*   [LinkedList](javacode/codeSamples/LinkedList.java). Similar to the LinkedList developed in class. Does not contain all the methods you would expect of a LinkedList. Also implements the iterator remove method in O(N) time. An O(1) time remove method is possible.
    
*   [UnsortedHashSet](javacode/codeSamples/UnsortedHashSet.java) \- An unsorted set that uses a hashtable with closed address hashing to store values. Currently only the add method is implemented.
    
*   [UnsortedSetTest](javacode/codeSamples/UnsortedSetTest.java) - A method to compare Java's TreeSet and HashSet to the BianrySearchTree, UnsortedSet, and UnsortedHashSet classes developed in class. Note you need a lot of other files for this to work.
    
*   [SimpleWordCount](javacode/codeSamples/SimpleWordCounter.java) \- Program demonstrating use of a map to count the frequency of words in a file.
    
*   [WordCount](https://www.cs.utexas.edu/~scottm/cs314/javacode/CodingSamples/WordCount.java) \- Program  that compares counting words in files using an ArrayList and a Map.