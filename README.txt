Merry Christmas, mom! I hope this script will be fun and helpful for you — making the perfect seating chart can be a painstaking process, but my script finds one in under a second. Hopefully this will be a useful timesaver.

Below I have a few things to note, including a description of how to execute the script.

              ~~~~~~~~~~~~~~

1. This script takes a list of tables and their sizes followed by a list of students and their attributes. Tables should be entered as such: 

Table Number, Capacity
(ex: 1, 5) or (2, 4)

And students should be entered as follows:

Name, Antsy?, Struggling?, Current Partner, Current Table
(ex: Nick, N, Y, none, 2) or (Maria, Y, Y, David, 1)

              ~~~~~~~~~~~~~~

2. This script takes three things into consideration when pairing up students and seating them at tables:
-Struggling students are partnered with students who are not struggling,
-antsy students are not partnered with other antsy students, and
-no student will sit with his or her previous partner.
The script also randomly shuffles the new pairs around to get students sitting at new tables, if possible.

              ~~~~~~~~~~~~~~

3. To run the script, follow these steps:

-Make a new folder on your desktop called “seatingChart_files”.
-Open “Terminal” from your applications. Wait for it to open and for a curser to appear.
-Type “cd Desktop/seatingChart_files“ and hit enter
-Then, type “python seatingChart” and hit enter

This will begin the execution of the program. You’ll then be prompted to enter the table and student info. I recommend writing it all out in an external file, then pasting it into the program. After that, it will output a new seating chart! If for some reason you’re not satisfied, running the program again will give another, equally viable seating chart (there are many combinations). I hope this helps! Love you!

              ~~~~~~~~~~~~~~

(12/25/15; all code, comments, and files were written by Zachary Blickensderfer; all rights reserved)