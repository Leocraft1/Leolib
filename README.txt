Welcome to the Leolib's WIKI! [Current Version: 0.2.1]

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
- sortAscending (returns an array sorted in ascending mode)
- sortDescending (returns an array sorted in descending mode)
- arrayOut (automatically prints the given int array)
The class arrayFloat contains the following methods:
The class arrayDouble contains the following methods:
The class arrayString contains the following methods:
The class stringUtils contains the following methods:
- isBlank (method to do isBlank in java version less than JDK 8)



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

----------------------METHODS-SYNTAX-----------------------

Information about each method mean can be found under the METHODS chapter.

# <returnType>=class.method(<parameters>);

Starting with the arrayUtils package we have:

# <int>=arrayInt.count(<int array to search in>, <int to count>);

# <int>=arrayInt.search(<int array to search in>, <int to search>);

# <int[]>=arrayInt.searchIndex(<int array to search in>, <int to search>);

# <int[]>=arrayInt.sortAscending(<int array to sort>);

# <int[]>=arrayInt.sortDescending(<int array to sort>);

In the class stringUtils has:

# <boolean>=stringUtils.isBlank(<String to see if it's blank>);

No Copyright, feel free to use this in your project, from the smallest to the biggest and even make mods.

Leo_craft1, 2023-2024
