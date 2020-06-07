# NaN-None
NaN and None in NumPy and Pandas

<img src = "NAN.png">

## NAN and None in NumPy

### NONE : Python's Singleton Object used for Missing Data.

**As a Python Object None cannot be used in any Arbitrary NumPy / Pandas Array.**

**But None can be used in Arrays with Data Type Object**

**Unlike other Objects we cannot perform Aggregations like sum() or min() across an Array with a None Value, we will generally get an Error.**

**Addition between an Integer and None is Undefined.**

### NAN : Missing Numerical Data

**NAN is a Special value which is part of the IEEE Floating Point Specification.**

**NAN is a Floating Point Value, there is no Equivalent NAN values for Integers, Strings and other Data Types.**

**NAN is bit like a Virus, it Infects any other Object it Touches, Means the Arithmetic with NAN will give another NAN.**

---------------------------------------------------------------------------------------------------------------------------

## NAN and None in Pandas

**Pandas handles both Interchangeably, Converting them where Appropriate.**

**Pandas Automatically Typecasts when Missing Values (NaN) and Null Values are present**

**The Moment we Add a None or NaN in Integer Series it will type cast to Float Point type**

## Operating on Null Values

**Pandas uses None and NaN as Interchangeable for indicating Missing Values and Null Values.**

**There are several useful Methods in Pandas for Detecting, Replacing and Removing Missing and Null Values.**
