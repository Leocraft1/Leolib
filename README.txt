Welcome to the Leolib's WIKI! [Current Version: 0.3]

Here are the instructions on how to use my java library: syntax, functions, methods and all other useful informations about this project.

------------------------------------------------------------
----------INSTALLING THE LIBRARY (NetBeans IDE)-------------
------------------------------------------------------------

Requisites:
- Java JDK 8 or newer
- Apache NetBeans (whatever version you have)

Installation:
- Download the library JAR file from the releases tab
- Open your NetBeans IDE
- Create a project or open an older one
- On the project explorer on the left, expand the project you want to install it to
- Right click on the "Libraries" folder
- Click Add JAR/Folder
- Locate the JAR file you just downloaded
- Click Done
You've now successfully installed my library in your java app.

INSTALLING AS DEFAULT
(Work in progress)

------------------------------------------------------------
-------------------------METHODS----------------------------
------------------------------------------------------------

There are a lots of useful methods in this library, mostly very basic but they will save your time; all the syntaxes are under the SYNTAX chapter.

The library has these packages:
- leolib
Inside leolib:
- arrayUtils (package)
- arrayString (class)
The package arrayUtils contains:
- arrayInt
- arrayFloat (Work in progress)
- arrayDouble (Work in progress)
- arrayString (Work in progress)
The class arrayInt contains the following methods:
- count (counts how many times an INT is present in the array, if not there it returns 0)
- search (boolean value, returns true if the INT is in the given array)
- searchIndex (returns an array with the index of all the positions of the INT in the given array)
- sortAscending (returns an array sorted in ascending mode, it is possible to specify a sorting type)
- sortDescending (returns an array sorted in descending mode, it is possible to specify a sorting type)
- outArray (automatically prints the given int array)
- merge (merges 2 arrays in one ordered array)
- isSorted (true if the given array is sorted in ascending or descending mode)
- outIndex (use this method ONLY if you want to print indexes, basically the same as outArray but adds 1 to every number)
The class arrayFloat contains the following methods:
The class arrayDouble contains the following methods:
The class arrayString contains the following methods:
The class stringUtils contains the following methods:
- isBlank (method to do isBlank in java version less than JDK 11)
- containsIndex (returns an array with all the indexes of the given char)



------------------------------------------------------------
-------------------------SYNTAX-----------------------------
------------------------------------------------------------

This chapter is about the methods' syntax; if you don't know how to call a static method in a library, this can be done with:

# <desired class name>.<desired method name>(<arguments>);

Example:

# arrayUtils.searchIndex(array, toSearch);

Remember to IMPORT the desired package you want to use before entering the file's class, this can be done with:

# import <library name>.<desired package>.<desired class>;

Example:

# import leolib.arrayUtils.*;

You can also import the class as STATIC: 

# import static <library name>.<desired package>.<desired class>.<desired method or *>;

Example:

# import static leolib.arrayUtils.arrayInt.*;

Calling the mothod like this: 

# <desired method name>(<arguments>);

Example:

# searchIndex(<arguments>);

----------------------METHODS-SYNTAX-----------------------

Information about each method mean can be found under the METHODS chapter.

# <returnType>=class.method(<parameters>);

Starting with the arrayUtils package we have:

# <int>=arrayInt.count(<int array to search in>, <int to count>);
# <boolean>=arrayInt.search(<int array to search in>, <int to search>);
# <int[]>=arrayInt.searchIndex(<int array to search in>, <int to search>);
# <int[]>=arrayInt.sortAscending(<int array to sort>, <OPTIONAL String sorting method. POSSIBLE VALUES: selection, bubble, insertion. DEFAULT: selection>);
# <int[]>=arrayInt.sortDescending(<int array to sort>, <OPTIONAL String sorting method. POSSIBLE VALUES: selection, bubble, insertion. DEFAULT: selection>);
# <void>=arrayInt.outArray(<int array to output>);
# <int[]>=arrayInt.merge(<int array to merge>, <int array to merge>, <String sort types. POSSIBLE VALUES: ascending, descending);
# <boolean>=arrayInt.isSorted(<int array to verify>, <String sort types. POSSIBLE VALUES: ascending, descending>);
# <void>=arrayInt.outIndex(<int array to output>);

In the class stringUtils has:

# <boolean>=stringUtils.isBlank(<String to see if it's blank>);
# <int[]>=stringUtils.containsIndex(<String to search in>, <char to search>);

No Copyright, feel free to use this in your project, from the smallest to the biggest and even make mods.

Leo_craft1, 2023-2024
