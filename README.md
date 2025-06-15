# Performer_Scheduler
Google Sheets code to organise your performers. Provides running orders for shows that avoids back-to-back performances, ideal for avoiding rapid costume changes during your dance school performance.
HOW TO:

-Create a new google sheet titled "Performer Schedule Input".

-Create the following columns*:
Performance Name	|  Performers	|  Constraints | Spacing

NOTE: The order of these columns shouldn't matter, but must be named as above.

-Open code editor: Google Sheets > Extensions > Apps Script

-Delete all text in code writer, then copy and paste the code from "PerformanceScheduler"

-Save and Run. Google may ask you for permissions, allow all. May throw errors from undefined column data.

May take a while depending on the number of variables. 13 dancers among 11 dances took around 3 seconds to generate once error messages are closed.

3 different running orders should be generated in a tab of your "Dance Performance Schedule" sheet, along with any clashes.

Note: Constraints field takes the inputs "first" and "last". If not either then leave the field blank.
Remember: If you do not code, you should always check random internet script through an ai.

*
Performance name = the title of this show/section.
Performers = the names of the performers involved, each separated by a comma.  eg. Alice,Bob,Claire,David
Constraints = only takes "first" or "last", optional, can be left blank.
Spacing = ideal minimum number of performances until a performer must return.
