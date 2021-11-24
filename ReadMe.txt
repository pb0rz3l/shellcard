       ______+_______________+_____________________________________+
      /    ##     /           /           /    +      /           //
     + ########  /+ ##   ##  /  #######  /  ##       /  ##       //_
    / ##        /  ##   ##  /  ##      +/  ##       +  ##    +  //__
   /   ##### + /  #######  /  ######   /  ##       /  ##       // __
  /        ## /  ##   ##  +  ##       /  ##    +  /  ##       //_ __
 /  ######## /  ##   ##  /  #######  /  #######  /  #######  // __ _
/__+__##____/___________/___________+___________/_______+___// _____

$ shellcard -- A minimal program for barbaric flash card reviews.
|
|   Spend the precious time
|                            not compiling good cards but
|         playing more shellcard.
|
$ Compile and accumulate flash card data in a plain text file:
|
|   level<tab>name 1<tab>name 2<tab>......<tab>name N
|   0.000<tab>data 1<tab>data 2<tab>......<tab>data N
|   0.000<tab>data 1<tab>data 2<tab>......<tab>data N
|   .....<tab>......<tab>......<tab>......<tab>......
|   0.000<tab>data 1<tab>data 2<tab>......<tab>data N
|
|   Namely a table of tab-separated values.
|   Then this program will be in aid of your study.
|
$ Available commands:
|
|   # to show this help information
|   shellcard help
|
|   # to review a flash card collection
|   shellcard review <file> [<option>=<value>]...
|
|   # to give your memory an examination
|   shellcard test <file> [<option>=<value>]...
|
|   # to show statistics about card decks
|   shellcard stat <file> [intervals=<value>]
|
|   # to check integrity of the database
|   shellcard check <file>
|
|   # to reset your progress of practice
|   shellcard reset <file>
|
$ Common options:
|
|   # maximum number of cards (default: all/review, 100/test)
|   cards=<integer>
|
|   # front side(s) of cards (default: 2nd column in the table)
|   front=<comma,separated,column,names>
|
|   # back side(s) of cards (default: 3rd column in the table)
|   back=<comma,separated,column,names>
|
|   # intervals between reviews as the proficiency level goes up
|   # units of time: (d) - day, w - week, m - month, y - year
|   # default: 1,2,3,5,8,13,21,34,55,89,<x> (231 days in total)
|   intervals=<comma,separated,intervals>
|
$ May you succeed with the Leitner spaced repetition system!
