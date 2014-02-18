README


-- added the new tests 201-215 as of feb 17 at 7:45 pm.

Credit to Renato Recio for originally making this script.

I only changed it to also use the new tests (16? to 27) and also to not sleep for one second between tests

NOTE: This script will say you failed the test unless your output exactly matches the sample output. Since sometimes there are more than one correct assignment of rooms to bids that produce the same max weight, it could be the case that your program produces a correct assignment which is not the one used by the sample outout. In this case, the test script will say that you failed that test when really you passed.


-------------------------------------
Renato's Original readme below
-------------------------------------

NOTE: If your program takes longer than 1 second to run, please run the slower version (./testslow) This version will take 1 minute and 30 seconds to complete


-To use this testing script, put your files in the project1 folder (run, build, assignment1, etc)

-Make sure not to alter the subdirectory or its contents

-When you are ready to run the program, run the  “test” file (type ./test) and wait for the process to complete. Do not end it early, as there will be files cp’d into your project1 folder. (If it ends early, make sure to remove all the extra files in your project1 folder — not your testfiles folder)

-For all the tests that have failed, there will be a diff log in the project1 folder

-The script uses diff -w to ignore all white space

-This script is NOT guaranteed to work, please use it as a tool to help find errors



