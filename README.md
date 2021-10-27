# Python-Basics
In-print('Hello World')
Out-Hello World

#Addition
In-a=4+4
In-a
Out-8

#Lists
In-list1=[10,20,30,50,40,60,90]
In-list1
Out-[10, 20, 30, 50, 40, 60, 90]
 list1.reverse()
>>>
>>> max(list1)
90
>>> list1
[90, 60, 40, 50, 30, 20, 10]
>>> list1.append()
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: list.append() takes exactly one argument (0 given)
>>> list1
[90, 60, 40, 50, 30, 20, 10]
>>> list1.append(100)
>>> list1
[90, 60, 40, 50, 30, 20, 10, 100]
>>> list2=list1.copy()
>>> list2
[90, 60, 40, 50, 30, 20, 10, 100]
>>> list1.index(20)
5
>>> list1.insert(3,99)
>>> list1
[90, 60, 40, 99, 50, 30, 20, 10, 100]
>>> list1.remove(100)
>>> list1
[90, 60, 40, 99, 50, 30, 20, 10]

>>> a=['apple','ball']
>>> b=a
>>> b
['apple', 'ball']
>>> b[1]
'ball'
>>> b[0]
'apple'
>>> b[1]='cat'
>>> a,b
(['apple', 'cat'], ['apple', 'cat'])
>>> a=['apple','ball']
>>> b=a.copy()
>>> b
['apple', 'ball']
>>> b[1]='cat'
>>> a,b
(['apple', 'ball'], ['apple', 'cat'])
  
#Tuple
>>> tuple1=1,56,8,64,'hy',4
>>> type(tuple1)
<class 'tuple'>
>>> tuple[5]
tuple[5]
>>> print(tuple[5])
tuple[5]
>>> tuple1[5]
4
>>>
>>> tuple1[4]=1
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'tuple' object does not support item assignment
>>> #Tuple is Immutable.
>>> #Lists are Mutable.
  
Possible to convert tuple to list and vice versa using the list() and tuple() commands respectively.
  
# Set
 set1={1,252,5,6,48,33,'aa','asd','box'}
  set1
  {1,252,5,6,48,33,'aa','asd','box'}
  
  #### {}=set, ()=tuple, []=list####

  
  
  
  **Creating a Array, Numpy=Package for Multidimensional array**

import numpy as np
simple_list=[1,8,9,79,15,45,13]
np.array(simple_list)
array([ 1,  8,  9, 79, 15, 45, 13])
arr
arr=np.array([1,8,9,79,15,45,13])
arr
array([ 1,  8,  9, 79, 15, 45, 13])
[4,5,6],[23,43,13,212,4],[325,43,21,34]
lol1=[[4,5,6],[23,43,13,212,4],[325,43,21,34]]
lol1
[[4, 5, 6], [23, 43, 13, 212, 4], [325, 43, 21, 34]]
1
np.array(lol1[1])
array([ 23,  43,  13, 212,   4])
np.zeros(4)
array([0., 0., 0., 0.])
8,59
np.arange(8,59)
array([ 8,  9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24,
       25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41,
       42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58])
np.zeros(8,dtype=int)
array([0, 0, 0, 0, 0, 0, 0, 0])
4
np.ones(4)
array([1., 1., 1., 1.])
5,dtype=int
np.ones(5,dtype=int)
array([1, 1, 1, 1, 1])
1,8,79,82
np.linspace(1,8,79,82)
array([1.        , 1.08974359, 1.17948718, 1.26923077, 1.35897436,
       1.44871795, 1.53846154, 1.62820513, 1.71794872, 1.80769231,
       1.8974359 , 1.98717949, 2.07692308, 2.16666667, 2.25641026,
       2.34615385, 2.43589744, 2.52564103, 2.61538462, 2.70512821,
       2.79487179, 2.88461538, 2.97435897, 3.06410256, 3.15384615,
       3.24358974, 3.33333333, 3.42307692, 3.51282051, 3.6025641 ,
       3.69230769, 3.78205128, 3.87179487, 3.96153846, 4.05128205,
       4.14102564, 4.23076923, 4.32051282, 4.41025641, 4.5       ,
       4.58974359, 4.67948718, 4.76923077, 4.85897436, 4.94871795,
       5.03846154, 5.12820513, 5.21794872, 5.30769231, 5.3974359 ,
       5.48717949, 5.57692308, 5.66666667, 5.75641026, 5.84615385,
       5.93589744, 6.02564103, 6.11538462, 6.20512821, 6.29487179,
       6.38461538, 6.47435897, 6.56410256, 6.65384615, 6.74358974,
       6.83333333, 6.92307692, 7.01282051, 7.1025641 , 7.19230769,
       7.28205128, 7.37179487, 7.46153846, 7.55128205, 7.64102564,
       7.73076923, 7.82051282, 7.91025641, 8.        ])
1,5,6
np.linspace(1,5,6)
array([1. , 1.8, 2.6, 3.4, 4.2, 5. ])
,dtype=int
np.linspace(1,9,5,dtype=int)
array([1, 3, 5, 7, 9])
6
np.eye(6)
array([[1., 0., 0., 0., 0., 0.],
       [0., 1., 0., 0., 0., 0.],
       [0., 0., 1., 0., 0., 0.],
       [0., 0., 0., 1., 0., 0.],
       [0., 0., 0., 0., 1., 0.],
       [0., 0., 0., 0., 0., 1.]])
3,dtype=int
np.eye(3,dtype=int)
array([[1, 0, 0],
       [0, 1, 0],
       [0, 0, 1]])
4
np.random.rand(1,4)
array([[0.30753816, 0.04788346, 0.42019988, 0.4510622 ]])
3,5
np.random.rand(3,5)
array([[0.22480929, 0.53221434, 0.89661938, 0.17690228, 0.86715018],
       [0.08984133, 0.47262491, 0.84281976, 0.64871236, 0.17791502],
       [0.10386976, 0.82824362, 0.38982461, 0.40675119, 0.19159939]])
2,4
np.random.randn(2,4)
array([[ 2.04498283, -1.78397733, -0.67101938, -0.65445948],
       [-1.12346038,  1.56892793,  1.06594152,  0.6172661 ]])
np.random.randint(0,5,16)
array([4, 2, 0, 3, 3, 2, 0, 1, 4, 0, 0, 0, 2, 3, 2, 1])
,66
np.random.randint(3,87,66)
array([19, 69, 23, 25, 11, 78, 58, 73,  4, 16, 39,  3, 65, 53, 48, 71, 19,
        8, 11,  3, 49, 32, 57, 86, 39, 13, 72, 58, 61, 81, 55, 48,  3, 31,
       61, 63, 83, 86, 25, 47,  3, 37, 21, 75, 54, 32, 71, 83, 81, 75, 75,
       72, 60, 41, 63, 57, 79, 35, 29,  6,  7, 11, 73, 39, 83, 51])
sample_array
sample_array=np.arange(5,15)
sample_array
array([ 5,  6,  7,  8,  9, 10, 11, 12, 13, 14])
sample_array.min()
sample_array.min()
5
max()
sample_array.max()
14
sample_array.argmin()
sample_array.argmin()
0
sample_array.argmax()
sample_array.argmax()
9
_array
sample_array=sample_array.reshape(2,5)
sample_array
array([[ 5,  6,  7,  8,  9],
       [10, 11, 12, 13, 14]])
sample_array
sample_array[1]=4
sample_array
array([[5, 6, 7, 8, 9],
       [4, 4, 4, 4, 4]])
sample_array
sample_array=np.arange(15,90)
sample_array
array([15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31,
       32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48,
       49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65,
       66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82,
       83, 84, 85, 86, 87, 88, 89])
:
sample_array[1:20]
array([16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32,
       33, 34])
subset_sample_array
subset_sample_array=sample_array[0:8]
subset_sample_array
array([15, 16, 17, 18, 19, 20, 21, 22])
subset_sample_array[2]=25
subset_sample_array
array([15, 16, 25, 18, 19, 20, 21, 22])
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
