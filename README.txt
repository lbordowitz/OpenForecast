OpenForecast is a package of general purpose, forecasting models written in Java that can be applied to any data series. One of the design goals is to make it easy for a developer to use in an application even if they do not understand, or care to understand, the differences between the different forecasting models available.

Requirements
============

To build OpenForecast, you will need the following tools:

 - a Java compiler (works with J2SDK 1.3 and above)
 - Maven build tool

Using OpenForecast
==================

To use OpenForecast in a Maven project, include this in your dependencies:

<dependency>
  <groupId>com.github.lbordowitz.openforecast</groupId>
  <artifactId>openforecast</artifactId>
  <version>0.5.0</version>
</dependency>


Building OpenForecast
=====================

The command "mvn clean package" will produce a .jar file in the target directory, which can be used in any project.


Steven R. Gould
openforecast@stevengould.org
