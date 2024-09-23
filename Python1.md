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
