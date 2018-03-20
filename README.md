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

#### Challenge 3: From a Domain Model to a Feature Test

We set variable docking_station equal to DockingStation.new and got an error.

backtrace
```
NameError: uninitialized constant DockingStation
	from (irb):1
	from /Users/lorrainephillips/.rvm/rubies/ruby-2.4.1/bin/irb:11:in `<main>'

```
We researched what a stacktrace/backtrace was and watched the feature testing video.

From our understanding the error was because we hadn't initialised the Constant, i.e. we hadn't created the DockingStation Class yet.


#### Challenge 4: Errors are good

```
featuretest.rb:5:in `<main>': uninitialized constant DockingStation (NameError)
```
Type of error: NameError
File path:
```
[jihinip:~/Projects/borisbikes]    #From Jihin's computer
/Users/lorrainephillips/.rvm/rubies/ruby-2.4.1/bin/irb:11:in    #From Lorraine's computer
```
Line number: 1 for Lorraine, 5 for Jihin


Here is another error code showing the same thing. We have agreed that when an error code comes up, it would usually be a good idea to research into the error type. In this case, it is NameError.
We agreed that we should define the constant to directly fix this error.

#### Challenge 5: From Feature Tests to Unit Tests

The difference between the error codes is that the error happened within the rspec file. The error name and detail was the same.
