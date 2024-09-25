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
