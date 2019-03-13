>>>
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
