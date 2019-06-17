# EE_Test
This Repo is for Validation of  the EE Test page .
==================================================

ASSUMED REQUIREMENTS
====================
1>The Web Application should work similarly on all Browsers
2>The Web Application should work similarly on not just Laptop/Desktops but also Mobile Devices
3>The Web Applications shall have a predictable and defined load time irrespctive of the number of Booking records it contains[LOAD TIME - TBD]
4>The User Credentials - First Name and Surname - shall have defined lengths and shall not take special characters other than "." [LENGTH - TBD]
5>The Price Input shall be restrcited to a specific length only and will have a MAX OF ONLY 2 digit decimal denoting the currency denomination   [LENGTH - TBD maybe 12 digits for ex: 1234567890.89]
6>The Check-In and Check-Out dates shall not be in the past.They shall always be current or in the future
7>The Check-Out Date shall always be equal to or later than the Check-In Date.

CONTENTS
==========
1>TestCases.xlsx 
=================
 a>Contains the list of Test Cases which have been recorded/executed
 b>NOTE- Even though there were no explicit requirements provided,certain requirements have been assumed while deriving the tests.
 c>It also has a list of Issues observed 
 =======================================
 
2>EqualExpertsHotelBooking_v001.zip
====================================
 a> SpecFlow[Cucumber for .Net] based Test Automation Solution 
 b> Built using .Net 4.7.2 and Specflow 3
 [NOTE - This version of specflow mandates the use of specfic libraries to generate the Code Behind files which actually run the test]
 c>Other advancements that can be done are:
 ==========================================
    # Conversion of this test solution to Command Utility driven method which allows it to be integrated to a CI/CD flow
    # Include PEN/SECURITY Test Automation as required
    # Include Automated Simulation of Multiple Users using Jmeter/equivalent..
 
 

