SmartObjectARX
==============

##What is this

A easy-include version of AutoCAD ObjectARX include files

## Ready to Work

* copy all files `which is without extension` to `inc` folder of ObjectARX

OR

* customize the `filepath` in gen2.py
* run gen2.py to generate the files

##How to Use 

###include AcDbEntity Class Declare
before 'include the file name'
```
#include <dbmain.h>
```
after 'include the class name '
```
#include <AcDbEntity>
```

##About Project

The project is based ObjectARX 2012 / Python 
Only support class right now, no struct,no enum, no global functions 

##DONE & ENJOY