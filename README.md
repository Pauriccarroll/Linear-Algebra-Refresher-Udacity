# Pig Latin Translator - Python 
# Course : Codeacademy-Learn Python

pyg = "ay"
original = raw_input(What is your name?)
if len(original) > 1 and original.isalpha:
word = original.lower()
first = word[1]
new_word = word + first + pyg
new_word = new_word[1:]
  print new_word
else:
  print "That isn't your name?'

