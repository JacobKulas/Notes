/ <- division
// <- division but then only take the whole number (no rounding)
% <- Take the remainder
3 ** 4 <- 3 to the power of 4


'{} {}!'.format('Hello', 'World') <- The parenthesis serve as slots for the inputs. This would print: Hello, World! 
'{}+{}={}'.format(1,2,3) <- 1 + 2 = 3


tuple/list Makes a list like thing. Tuples are unchangeable 'unmutable'
d = list('Hello world')
d[0] 'H'
d[-1] 'd'
lst = []  <- blank list
tpl = ()  <- blank tuple

.append allows you to append to the end of a list
dlist.append('!') <- This adds ! to the end of the list

.join() allows you to join lists together
'*'.join(dlist) adds a star between every chracter

.split() allows you to split a string based off a delmiter
passwd.split(':') <- splits the file 'passwd' into a list based off the delimiter 

dlist[0] = 'j' <- changes the first thing in dlist to j

EX: 
email = 'name@domain.com' <- an email
a = email.split('@') <- email into [name , domain.com]
b = '.'.join(a)  <- 
c = b.split('.')
print(c)
'''

input('Type something:') <- accepts an input and prompts user to "type something"
print(usr)

Proper syntax for if, elif, else
If a == True:
  print('yamotha')
elif b == yamotha:
  print ('yafatha')
else:
  print('yafatha')

a = email.split('.')

def Commands()    
 2     while True:
 3         user = input("Type 'Pass', 'Break', 'Continue', or 'Return':\n").lower()
 4         if user == 'pass':
 5             pass
 6             print('This is pass.')
 7         elif user == 'break':
 8             break
 9             print('This is break')
10         elif user == 'continue':
11             continue
12             print('This is continue')
13         elif user == 'return':
14             return 'This is return'
15         else:
16             print('Please choose a valid option')

list(range(0,11,2)) <- Goes from 0 to 11 by increments of 2

catalog - {'Apex': 50,'Cod':79.99,'MVP':154.99,'Tarkov':200} <- Each of the game names is a key, the number are associated with them
order = [('MVP', 5),('Tarkov',2)] <- two lists inside one list
for i in order;
  print(catalog[i[0]] * i[1])      #<- This says that for every item in order (The items are lists) take the first things from said list. Then multiply it by the second thing in that list.
  total += catalog[i[0]] * i[1]    #<- This says that each time the loop runs it will add to the variable total
print(total)

OPEN METHODS
  r 'read'
  w 'write'
'''
fp = open('test.txt')
fp.close()
'''
fp.read(5) reads the first 5 characters
fp.readline() reads lines
fp.readlines() reads lines and makes them a list
print(line, end='**') <- print each line then add **
----------------------------------------------------------------------------------- <- This script writes first line second line\n, third line\n, fourth line\n last line\n to a document called test.txt
with open("test.txt",'w') as fp:
  fp.write('First line'\)
  lines = ['Second line\n', 'Third line\n', 'Fourth line\n', 'Last line\n'] 
  fp.writelines(lines)
  pass
------------------------------------------------------------------------------------
with open('school_prompt.txt','r') as fp:
    p_words = []
    for word in fp:
        for letter in word.split():
            if 'p' in letter:
                p_words.append(letter)
---------------------------------------------------
with open('travel_plans.txt','r') as fp:
    first_chars = fp.read(33)
--------------------------------------------------
with open('emotion_words.txt','r') as fp:
  emotions = []
  for l in fp.readlines():
      emotions.append(l.split(' ')[0])
---------------------------------------------------
with open('school_prompt.txt','r') as fp:
    three = []
    for l in fp.readlines():
        three.append(l.split(' ')[2])
---------------------------------------------------
with open('emotion_words.txt','r') as fp:
     num_words = len(fp.read().split())
---------------------------------------------------
ord
chr
'1'.isnumeric -> true   These work only on strings
'a'.isnumeric -> false
----------------------------------------------------
-----------------------------------------------------------------------
 -------------------------------------------------------------------------
3 
  Given a list (lst) and a number of items (n), return a new 
  list containing the last n entries in lst.
lst =[1,2,3,4,5]
n = 2

return(lst[-n::])



  
4 Given an input stgring, return a list containing the ordinal numbers of each character in the string in the order found in the input string
def q4(string):
  lst = []
  for i in string
    lst.append(ord(i))
  return lst


8 def q8 (filename):
    with open (filename,'w') as fp:
      for word in lst:
        if word.lower() == 'stop':
          break
        else:
          fp.write('{}\n'.format(word))
    pass

9 if 300 <= miltime < 1200:
    return "Good Morning"
  elif 1200 <= miltime < 1600:
    return "Good Afternoon"
  elif 1600 <= miltime < 2059:
    return "Good Evening"
  else:
    return "Good Night"

10
for num in numlist:
  if num < 0:
    return(False)
return(True)
    



















def q1(floatstr):
  4     '''
  5     TLO: 112-SCRPY002, LSA 3,4
  6     Given the floatstr, which is a comma separated string of
  7     floats, return a list with each of the floats in the 
  8     argument as elements in the list.
  9     '''
 10     b = floatstr.split(',')
 11     newlst = []
 12     for flt in b:
 13         newlst.append(float(flt))
 14     return(newlst)
 15     pass
 16
 17 def q2(*args):
 18     '''
 19     TLO: 112-SCRPY006, LSA 3
 20     TLO: 112-SCRPY007, LSA 4
 21     Given the variable length argument list, return the average
 22     of all the arguments as a float
 23     '''
 24     total = 0
 25     for num in args:
 26         total += num
 27     b = total/len(args)
 28     return(b)
 29     pass
 30
 31 def q3(lst,n):
 32     '''
 33     TLO: 112-SCRPY004, LSA 3
 34     Given a list (lst) and a number of items (n), return a new 
 35     list containing the last n entries in lst.
 36     '''
 37     pass
 38 def q4(strng):
 39     '''
 40     TLO: 112-SCRPY004, LSA 1,2
 41     TLO: 112-SCRPY006, LSA 3
 42     Given an input string, return a list containing the ordinal numbers of 
 43     each character in the string in the order found in the input string.
 44     '''
 45     
 46     pass
 47
 48 def q5(strng):
 49     '''
 50     TLO: 112-SCRPY002, LSA 1,3
 51     TLO: 112-SCRPY004, LSA 2
 Given an input string, return a tuple with each element in the tuple
 53     containing a single word from the input string in order.
 54     '''
 55     a = (strng.split(' '))
 56     return(tuple(a))
 57     pass
 58
 59 def q6(catalog, order):
 60     '''
 61     TLO: 112-SCRPY007, LSA 2
 62     Given a dictionary (catalog) whose keys are product names and values are product
 63     prices per unit and a list of tuples (order) of product names and quantities,
 64     compute and return the total value of the order.
 65
 66     Example catalog:
 67     {
 68         'AMD Ryzen 5 5600X': 289.99,
 69         'Intel Core i9-9900K': 363.50,
 70         'AMD Ryzen 9 5900X': 569.99
 71     }
 72
 73     Example order:
 74     [
 75         ('AMD Ryzen 5 5600X', 5), 
 76         ('Intel Core i9-9900K', 3)
 77     ]
def q7(filename):
 93     '''
 94     TLO: 112-SCRPY005, LSA 1
 95     Given a filename, open the file and return the length of the first line 
 96     in the file excluding the line terminator.
 97     '''
 98 '''
 99     with open('filename','r') as fp:
100         a = (len(fp.readline()) -1)
101     return(a)
102     pass
103 '''
104 def q8(filename,lst):
105     pass    
106 '''
107     TLO: 112-SCRPY003, LSA 1
108     TLO: 112-SCRPY004, LSA 1,2
109     TLO: 112-SCRPY005, LSA 1
110     Given a filename and a list, write each entry from the list to the file
111     on separate lines until a case-insensitive entry of "stop" is found in 
112     the list. If "stop" is not found in the list, write the entire list to 
113     the file on separate lines.
114     '''
115 '''
116     for entry in lst:
117         if entry != 'stop':
118             with open('filename','w') as fp:
119                 fp.write(entry'\n')
120         elif entry == 'stop':
121             break
122 '''   
123
124 def q9(miltime):
125     '''
126     TLO: 112-SCRPY003, LSA 1
127     Given the military time in the argument miltime, return a string 
128     containing the greeting of the day.
129     0300-1159 "Good Morning"
def q10(numlist):
149     '''
150     TLO: 112-SCRPY003, LSA 1
151     TLO: 112-SCRPY004, LSA 1
152     Given the argument numlist as a list of numbers, return True if all 
153     numbers in the list are NOT negative. If any numbers in the list are
154     negative, return False.
155     '''


