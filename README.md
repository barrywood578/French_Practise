# French_Practise
# Simple challenge/response drill program for general French vocabulary and verb conjugation.
#
# Implemented in Python, tested on Linux and in a-shell on IOS.
#
# To invoke the program and receive current help information, use:
#
# > python vocab_drill.py -h
#
# To test 5 questions from each subject, use:
#
# > python vocab_drill.py -s 5
#
# To test 50 questions from general vocabulary, use:
#
# > python vocab_drill.py -s 50 -v
#
# Command line variables allow the user to limit which subjects (general vocabulary and/or
# various verb tenses), and how many questions in each subject, will be part of the drill.
# The variables are explained in the help.  The default is to drill all subjects, completely.
#
# The list of sample questions for each subject is selected when each subject starts.
# Incorrect responses result in the sample question being added to the end of the list,
# allowing the user to try again.  The next subject is started when all questions for the
# current subject have been answered correctly.
#
# The program can be halted by:
# - interrupting the program (Control <C>)
# - entering "Stop" as the response to any question
#
# Since entering characters with accents is generally difficult, all necessary "special"
# characters are printed before each question.  The user can copy and paste these characters
# into their response as necessary.
#
# French is a gendered language.  Instances where the gender is not clear use "(m)"
# and "(f)" to specify male and female usages, respectively.
#
# French has different words for singular and plural "you".  Singular is specified with "you",
# while plural "you" is specified with "y'all".
