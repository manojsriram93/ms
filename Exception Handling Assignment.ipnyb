#!/usr/bin/env python
# coding: utf-8

# In[2]:


##Write a function to compute 5/0 and use try/except to catch the exceptions
def div_by_0(a):
    try:
        c=a/0
    except Exception as e:
        print(e)


# In[3]:


x=5
div_by_0(x)

##Implement a Python program to generate all sentences where subject is in
##["Americans", "Indians"] and verb is in ["Play", "watch"] and the object is in
##["Baseball","cricket"].
import itertools
subject = ["Americans", "Indians"]
verb = ["play", "watch"]
obj = ["Baseball","cricket"]
sen=()
for combination in itertools.product(subject, verb, obj):
    sen = combination
    sen_iter = iter(sen)
    print(sen_iter*len(sen))
    
    
# In[39]:


mytuple = ("apple", "banana", "cherry")
myit = iter(mytuple)
print((next(myit))+(next(myit))+(next(myit)))


# In[57]:


##Implement a Python program to generate all sentences where subject is in
##["Americans", "Indians"] and verb is in ["Play", "watch"] and the object is in
##["Baseball","cricket"].
import itertools
subject = ["Americans", "Indians"]
verb = ["play", "watch"]
obj = ["Baseball","cricket"]
sen=()
for combination in itertools.product(subject, verb, obj):
    sen = combination
    print(sen[0]+" "+sen[1]+" "+sen[2])


# In[ ]:




