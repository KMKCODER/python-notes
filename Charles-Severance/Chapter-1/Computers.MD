# Computers want to be helpful
Computers wan to do things but we need to speak their langauge to describe what we want done. instructions are put into the computer for a user to just pick and use.

## Users Vs Programmers
* Users see computers as a set of tools.
* Programmers learn the computer "ways" and the computer language.
* Programmers have some tools that allow them to build new tools.
* Programmers sometimes write tools for lots of users and sometimes programmers write "helpers" for themselves to automate a task.

## Why be a programmer?
* To get some tasks done as a a use and programmer.
* to produce something for others to use.
* A software developer wants to build the software.

## What is Code? Software? A Program?
* A sequence of stored instructions.
* A piece of creative art.

## Programs for Humans...
* In computers you have be prescise with instructions, never be implicit with expecting the computer to understand what you mean.

## Programs for Python.
* Computers are prescise with text analysis.
### Sample code.
* Count the number of words in this text.
> the clown ran after the car and the car ran into the tent and the tent fell down on the clown and the car.
#### Code sample 1
```python
  # Find the most common word in the text and state the number.
  name = raw_input ('Enter file:')
  handle = open(name)
  
  counts = dict()
  for line in handle:
      words  = line.split()
      for word in words:
          counts[word] = counts.get(word,0) + 1
 ```
 #### Result 1
 ```python
  pythonn words.py
 Enter file: words.txt
 to 16
 ```
 #### Code sample 2
 ```python
  # Find the most common word in the text and state the number.
  bigcount = None
  bigword = None
  for word,count in counts.items():
      if bugcount is None or count > bigcount:
          bigword = word
          bigcount = count
          
  print(bigword, bigcount)
```

#### Result 2
 ```python
 pythonn words.py
 Enter file: clown.txt
 the 7
 ```


