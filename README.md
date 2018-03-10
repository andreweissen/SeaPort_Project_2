### Object Oriented and Concurrent Programming, SeaPort Project 2 ###

#### Overview ####

The four-part SeaPort Project Series served as the primary means of concept enforcement in CMSC 335, Object Oriented and Current Programming. At its most basic level, the program employs the fundamental principles of object oriented programming and multithreading concurrency to chart the movements of hypothetical ships in a set of sea ports, processing their jobs in real time with the application of included dock workers and moving the vessels about from queue to dock to harbor as their jobs are completed.

Over the course of five projects, including the four required and an alternate Project 4, the author expanded a hand-drawn GUI constructed with Swing that provides users with a comprehensive overview of the world and its contents, in addition to a number of secondary utility features. Users are permitted access to a search function for any and all objects in the world, as well as a sorting option that lists objects by a number of user-selected parameters such as weight, draft, etc. Furthermore, each of the jobs in question is interactive, with the user given the ability to suspend, cancel, or complete ongoing jobs as desired.

#### About Project 2 ####

Project 2 of the SeaPort Project Series focused on a number of back-end optimizations meant to improve upon the manner in which world data is displayed and assembled, replacing several utility methods with `HashMap`s and using reflection to make remaining utility methods more readily usable in different situations. Furthermore, the user interface was further expanded from the single raw `toString()` world panel formerly constructed in the previous project to a three-panel design. The `JOptionPane` search popup was replaced by a dedicated log displaying the results of all searches, and a `JTree` representation was included alongside the aforementioned raw text output. Additionally, a sorting function was added to permit users to organize objects by a number of parameters.

Included are all files, documentation (notated as `Eissen_Project2.pdf`), and the project requirements rubrics (notated as `SeaPort_Project2_Rubric.pdf`).