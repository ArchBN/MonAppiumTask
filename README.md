# MonAppiumTask
To automate Monefy Android application




Tools:
Node.js
Java
Maven
TestNG
Appium Server
Appium Client Libraries
Selenium Libraries
Android Studio

Different levels if testing:

1.Functional tetsing:
It can be done at function level.It cannot be used at enduser level.
Advantages:
Easy to identify the bug and retest it.
Refactoring can be done easily.

Disadvantages:
It can't be used to test different applications for end result.User behaviour cannot be tested .


2.SIT:
It can be done using APK and other applications together.It mainky checks different API calls and the interfaces.

Advantages:
All the Interface level testing can be done early to find the bugs.
Disadvantages:
This can'check the end user UI and still app behaviour is unknown in this phase.

3.E2E Testing
 This is used to check behaviour of the app.
 Advantages:
  End user behaviour can be tested here before Go-live.
  This given confidence level for rolling out to prod.
 
 Disadvantages:
 Slow due to the diff systems connected

Approach:
Intellij Workspace

POM:POM file are easy to maintain and easily update the  dependicies .
Maven is also used to manage a project's build, reporting and documentation from a central piece of information and a project will be easy shared without having to lots of manual libararies downloading.
Appium
Appium is an opensource mobile testing tool,platform independent.Appium supported programming languages like Java, Javascript, C#, PHP, Python and Ruby. Appium can test native mobile apps, hybrid mobile apps and browser apps. Appium can be used with muliple framworks like data driven framwork and behavior driven.
