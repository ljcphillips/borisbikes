## Boris Bikes

We aim to write a program that will emulate all the docking stations, bikes and infrastructure required to make the Boris Bikes system a reality.

### Day 1 - Lorraine & Jihin

#### Challenge 1 Project Setup

We've set up together! -Lorraine and Jihin

#### Challenge 2: Working with user stories

###### Story 1 & 2

Objects | Messages
------------- | -------------
Person  |  Checks condition, use bike
Bike  |  
Docking station |  Releases bike

Jihin & Lorraine jotted down a diagram on a piece of paper.
Completed challenge 2!

#### Challenge 3 From a Domain Model to a Feature Test

We set variable docking_station equal to DockingStation.new and got an error.

backtrace
```
NameError: uninitialized constant DockingStation
	from (irb):1
	from /Users/lorrainephillips/.rvm/rubies/ruby-2.4.1/bin/irb:11:in `<main>'

```
We researched what a stacktrace/backtrace was and watched the feature testing video.

From our understanding the error was because we hadn't initialised the Constant, i.e. we hadn't created the DockingStation Class yet.
