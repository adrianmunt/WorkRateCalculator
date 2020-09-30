# WorkRateCalculator
Solution based on the following kata:
**************
The babysitter:

    starts no earlier than 5:00PM
    leaves no later than 4:00AM
    gets paid $12/hour from start-time to bedtime
    gets paid $8/hour from bedtime to midnight
    gets paid $16/hour from midnight to end of job
    gets paid for full hours (no fractional hours)

Feature

As a babysitter
In order to get paid for 1 night of work
I want to calculate my nightly charge
**************

Code is written in Java 11.0.6
Run from Windows command line (Run->cmd.exe)
Navigate to download directory (assume correct java version is installed)
java -jar WorkRateCalculator.jar

Source code is in src.zip
The code is divided into four modules:
WorkDay.java: This is a class encapsulating a WorkDay (a series of 'WorkPeriod's)
WorkPeriod.java: Class representing a period of the day which is worked at the same pay rate
WorkRateCalculator.java: Contains the main[] method and an interface implementation
WorkRateUI.java: An Interface representing the abstracted input and output methods for the application
