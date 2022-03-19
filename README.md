This tool implements a simple task list and reminder system.  The
input is simple text files, and the output is to the console.

A unique feature of this software is that the reminders can be
task rules can be set to provide reminders on a particular cadence,
such as:

   o Monday, Wednesday and Saturday
   o every 7th Tuesday
   o the second Thursday of every month
   o April 1st, every year.
   o the first of every month

A handy way to run this software is to launch it in a terminal via
'watch', like so:

   watch --interval=600 remindo

The default main input file is ~/.reminders/reminders, but that can be
changed with the '--idf' argument.
