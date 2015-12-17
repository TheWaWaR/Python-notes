# Python-Learning
notes on python-learning
###Define a function called reverse that takes a string textand returns that string in reverse.

For example: reverse("abcd") should return "dcba".

You may not use reversed or [::-1] to help you with this.
You may get a string containing special characters (for example, !, @, or #).###

No.1
def reverse(text):
    L=list(text)
    L.reverse()
    L=''.join(L)
    return L
    
No.2
text[::-1]

*******
"Can only iterable" Python error
...
list = text.reverse()
reve= ' '.join(list)
----------
error:
    reve = ' '.join(list)
TypeError: can only join an iterable

text.reverse(), like many list methods, acts in-place, and therefore returns None. So tobereversedlist1 is therefore None, hence the error.

You should pass splitlist1 directly:

------
a = '12345'
>>> print ''.join(list(a).reverse())
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: can only join an iterable

a = '12345'
>>> L=list(a)
>>> L.reverse()
>>> ''.join(L)
'54321'

>>> def sss4():
 w = 'sdfghj'
 j = len(w)
 n = []
 for i in range(j):
  s = w[i]
  n.append(s)
  if i == j-1:
   n.reverse()
   print n

>>> sss4()
['j', 'h', 'g', 'f', 'd', 's']

 

别人相对好点的方法

>>> def sss7():
 strtmp="abcdef"
 sbr=[]
 j=0
 for i in range(len(strtmp)-1,-1,-1):
   sbr.append(strtmp[i])
 print sbr

 
>>> sss7()
['f', 'e', 'd', 'c', 'b', 'a']

   
其实相对好点的程序，本题如果正规要求，应该也不能打满分。因为题目输入为字符串，输出也是字符串。两个程序都输出的不是正解。
