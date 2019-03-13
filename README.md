# String Manipulation
>>> string1 = "Don't give a fuck,"
>>> string2 = " Just fuck it"
>>> newstring = string1 + string2
# Adding 2 strings
>>> newstring
"Don't give a fuck, Just fuck it"
# Replacing a word in the string
>>> newstring = newstring.replace("fuck","chuck")
>>> newstring
"Don't give a chuck, Just chuck it"
# We can select the word positioning when the word is repeated more than once
>>> newstring = newstring.replace("chuck","fuck",1)
>>> newstring
"Don't give a fuck, Just chuck it"
# We can count the number of repeatitions of a particular word
>>> newstring.count("fuck")
1
# Lists
 list1 = ["a", "b", "c", "d", "e", "f"]
# append an element to the list
list1.append("g")/ list1 = list1 + ["g"]
list1 = ["a", "b", "c", "d", "e", "f", "g"]
# remove an element
list1.remove("g")
list1 = ["a", "b", "c", "d", "e", "f"]
>>> # converting a list to a string
... list1=''.join(list1)
>>> list1
'abcdef'
