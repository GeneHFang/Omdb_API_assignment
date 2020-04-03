Author: Gene Li (ghli1@asu.edu) and Tim Lindquist (Tim.Lindquist@asu.edu), ASU Polytechnic, CIDSE, SE
Version: January 2020

See http://pooh.poly.asu.edu/Ser321

Purpose: Gene H Li Assignment 2


IMPORTANT NOTES: series.json has been changed to seriesTest.json

This project is designed to run on either Debian Buster Linux or MacOS. It
requires jdk13.

Building and running the sample is done with Ant.
This example depends on the following frameworks:
1. Ant
   see: http://ant.apache.org/
2. Json for Java as implemented (reference) by Doug Crockford.
   See: https://github.com/stleary/JSON-java
3. Gluon's JavaFX for Java13 on Linux.
   See: https://gluonhq.com/products/javafx/

To build and run the example, you will need to have Ant installed on
your system, with the antlib target extensions.
(see the CppFraction example from unit1 material for installing these in your home directory).

Run the sample with the command:
ant sample -Domdbkey=place-your-omdb-key-here -DuserId=Tim.Lindquist

To clean the project directory:
ant clean

The project directory  includes docs directory containing the javadocs
for the instructor provided software for the user-interface view,
which you will use in creating your solution.

end
