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
    
#Given an email:
#<first>.<m>.<last>@<domain>.com
# return the 4 parts of the email as a tuple the same way they appear.
a = 'Jacob.t.kulas@gmail.com'
b = a.split('.')
f = b[0]
mi = b[1]
ldom = b[2].split('@')
l = ldom[0]
dom = ldom[1]
tpl = (f, mi, l, dom)
print(tpl)
#Given a string make a dictionary whose keys are the set of unique characters within the string and whose values are the count of occueances of each chatacter
a = 'Your mother is a very kind person'
count = 0
dict = {}
for letter in a:
    dict[letter] = a.count(letter)
print(dict)
#Return your last name as a string:
print('kulas')

Given a list and a number of items return a new list containing the last n entries in lst

lst = [1, 2, 3, 4, 5, 6, 7]
n = 3
    print(lst[-n::])


return the surface area of a sphere after being given the radius. The formula for SA of a sphere is provided

return(4*3.14159*(radius**2))


Given an IPv4 address as a string in dotted decimal notation,
# return True if the address is multicast, otherwise return False.
# IPv4 multicast addresses are those in the range 224.0.0.0 to
# 239.255.255.255.
# ipaddress.IPv4Address has been disabled for this function.
addr = '240.64.33.123'
a = addr.split('.')
b = int(a[0])
if 224 <= b <= 239:
    print(True)
else:
    print(False)

Return List of well known ports. Well known ports are 0 through 1023
lst = []
for x in range(1024):
    lst.append(x)
print(lst)


You're given 'zero' 'one' 'two' 'three' or 'four', Turn them into their integer
a = input('What number?: ')
if a == 'zero':
    print(0)
elif a == 'one':
    print(1)
elif a == 'two':
    print(2)
elif a == 'three':
    print(3)
elif a == 'four':
    print(4)

Read a string and extract the number then convert it to integer and return it. Assume every string has a number
a = 'I a in love2 with a bea4utiful g1rl wh0 actually want$ m3' #input('input a string with a number in it: ')
lst = []
for letter in a:
    if letter == '1' or letter == '2' or letter == '3' or letter == '4' or letter == '5' or letter == '6' or letter == '7' or letter == '8' or letter == '9' or letter == '0':
        lst.append(int(letter))
print(sum(lst))
print(lst)

Take a name and domain then print an email adress First.M.Last@Domain.com All lowercase. They will give a full middle name, only take the middle inital
fn = (input('Whats your First name?: ')).lower()
mn = (input('Whats your middle name?: ')).lower()
m = mn[0]
ln = (input('Whats your last name?: ')).lower()
dom = (input ('Whats your domain?: ')).lower()
print('{}.{}.{}@{}.com'.format(fn,m,ln,dom))


Copy the contents of infile to outfile overwrite it if it doesn't exist
infile = input('What file to read?: ')
outfile = input('What file to copy to?: ')
with open (infile) as fp:
    a = fp.read()
with open (outfile,'w') as fp:
    fp.write(a)


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
def q1(radius):
    # Given the radius of a sphere, calculate and return 
    # its surface area. Surface area is given by the following:
    # A = 4*PI*(r**2) where PI is the constant 3.14159 and r
    # is the radius of the sphere.

    return 4*3.14159*(radius**2)

    pass
    
def q2(addr):
    # Given an IPv4 address as a string in dotted decimal notation,
    # return True if the address is multicast, otherwise return False.
    # IPv4 multicast addresses are those in the range 224.0.0.0 to
    # 239.255.255.255.
    # ipaddress.IPv4Address has been disabled for this function.
    counter = 0
    arr = addr.split('.')
    if int(arr[0]) >= 224 and int(arr[0]) <= 239:
        return True
    else:
        return False
    if counter == 1:
        return True


    #pass

def q3():
    # Return the well-known ports as a list of integers.
    # Ports 0 through 1023 are considered well-known.

    arr = []
    for x in range(1024):
        arr.append(x)
    return arr

    pass

def q4(number):
    # Given a string for a number spelled out as a word,
    # return the number as an integer. The number will
    # only be 'zero','one','two','three', or 'four'.

    if number == 'zero':
        return 0
    elif number == 'one':
        return 1
    elif number == 'two':
        return 2
    elif number == 'three':
        return 3
    elif number == 'four':
        return 4


    pass

def q5():
    # Read a string from the user and return the integer conversion of it.
    # Ensure the conversion is successful by removing any non-numeric characters.
    # You may assume that the input will contain at least 1 numeric character.
    bruh = ''
    arr = ['0','1','2','3','4','5','6','7','8','9']
    a = input()
    for x in list(a):
        if x in arr:
            bruh += x
        else:
            continue
    return int(bruh)


    pass

def q6(first,middle,last,domain):
    # Given a name and domain, print to the screen their email address.
    # The address should take the form: 
    # <first>.<middle initial>.<last>@<domain>.com
    # Only include a middle initial (the first letter of the middle name).
    # Ensure the address is all lowercase.
    # Append '.com' to the given domain.
    
    print(f'{first.lower()}.{middle[0]}.{last.lower()}@{domain}.com')


    pass

def q7(infile,outfile):
    # Copy the contents of the file whose filename is given in 
    # infile to the file whose name is given in outfile. Overwrite
    # outfile if it already exists.
    # shutil.copyfile, copy, and copy2 have been disabled for this function.
    with open(infile, 'r+') as fp, open(outfile, 'w') as out:
        out.write(fp.read())
            

    pass

def q8(address):
    # Given an email address of the form:
    # <first>.<middle initial>.<last>@<domain>.com
    # return the 4 elements of the address as a tuple in the order
    # that they appear in the address.
    # For example, if given 'nicholas.r.yost@somedomain.com,
    # ('nicholas','r','yost','somedomain') should be returned.

    
    return tuple((address.replace('.com','')).replace('@','.').split('.'))

    pass

def q9(strng):
    # Given a string, return a dictionary whose keys are the set of
    # unique characters within the string and whose values are the
    # count of occurances of each character.
    # For example, if given 'hello', the returned dictionary should be
    # { 'l':2, 'h':1, 'e':1, 'o':1 }
    # collections.Counter has been disabled for this function.
    count = 0
    dict = {}
    for x in list(strng):
        dict[x] = strng.count(x)
    return dict
    
    pass    

def q10():
    # Return your last name as a string. Use all lowercase letters.
    pass

    return 'hunt'

if __name__ == '__main__':
    pass

