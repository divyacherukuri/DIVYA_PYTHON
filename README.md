# DIVYA_PYTHON
PYTHON
"""
Print output
"""
print("*************Print output**************")
print("1->",1)
print("2->",2.5)
print("3->",-34)
print("4->",3/4)
a=0
print("5->",a)
print("6->","a")
a=23
print("7->",a)
print("8->","This is DeKalb!!!")
print("9->",a)

"""
Numbers
"""
print("*************Numbers**************")
x=5
y=10
print("1.",x+y)
print("2.",x-y)
print("3.",x*y)
print("4.",x/y)
print("5.",y**x)
a=(x/y)+x-y
print("6.",a)
print("7.",x+1)
x+=1
print("8.",x)
print("9.",x-1)
x-=1
print("10.",x)

"""
String
"""
print("*************String**************")
fname='Huskie'
lname="Victor"
print("1->",fname)
print("2->",lname)
print("3->",fname,lname)
print("4->","First name is:",fname)
print("5->","Name: ",fname,lname)
print("6->",len(fname))
print("7->","Name: ",fname, "The",lname)

"""
List
"""
print("*************List**************")
instructorNames = list()
print("1.",instructorNames)
instructorNames.append("NIU")
print("2.",instructorNames)
instructorNames.append(25)
print("3.",instructorNames)
temporaryList = [22, 10, 35, 26, 99, 1002]
lengthOfList = len(temporaryList)
print("4.",lengthOfList)
print("5.",temporaryList)
temporaryList.insert(2,777)
print("6.",temporaryList)
delElement=temporaryList.pop(2)
print("7.",delElement)
print("8.",temporaryList)

"""
Dictionary
"""
print("*************Dictionary**************")
instructorNames = dict()
print("1->",instructorNames)
instructorNames['OMIS670'] = 'Huskie'
print("2->",instructorNames)
instructorNames['OMIS651'] = 'Victor'
print("3->",instructorNames)
instructorNames['OMIS651'] = 'Huskie The Victor'
print("4->",instructorNames)
OMIS670 = instructorNames['OMIS670']
print(OMIS670)

"""
Datatype
"""
a = 1
print("1.",type(a))
a = 1.0
print("2.",type(a))
aList = [0, 1, 2, 3]
print("3.",type(aList))
instructorNames = dict()
print("4.",type(instructorNames))

#Loop over a list
print("*************Using FOR loop to iterate a list*************")
myNewList = [1,2,3,4,5,6,"One","Two",0.5]
for item in myNewList:
    print(item)

#Loop with condition
print("*************Using FOR loop to iterate a list and IF condition to check if the item in list is a integer*************")
for item in myNewList:
    if isinstance(item,int):
        print(item, "is an integer")
    elif isinstance(item,str):
        print(item, "is a string")
    else:
        print(item, "is neither an integer nor a string")



#Loop over a dictionary
print("*************Using FOR loop to iterate a dictionary with key-value pairs*************")
myDictionary = {'key1':'value1','key2':'value2','key3':'value3','key4':'value4'}
for key,value in myDictionary.items():
    print(key,value)
