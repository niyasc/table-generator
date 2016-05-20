Table Generator
============

Quickly convert text data to tabular data in different formats.


## Sample Input

```
Col1	Col2	Col3
Value 1	Value 2	123
Separate	columns	with a tab or 4 spaces
This is a row with only one cell
```

## Sample Output

### ASCII Table (MySQL style)
```
+----------------------------------+---------+------------------------+
|               Col1               |  Col2   |          Col3          |
+----------------------------------+---------+------------------------+
| Value 1                          | Value 2 | 123                    |
| Separate                         | columns | with a tab or 4 spaces |
| This is a row with only one cell |         |                        |
+----------------------------------+---------+------------------------+
```

### ASCII Table (Alt. style)
```
+==================================+================================+======+
|               Col1               |              Col2              | Col3 |
+==================================+================================+======+
| Value 1                          | Value 2                        |  123 |
+----------------------------------+--------------------------------+------+
| Separate                         | columns with a tab or 4 spaces |      |
+----------------------------------+--------------------------------+------+
| This is a row with only one cell |                                |      |
+----------------------------------+--------------------------------+------+
```

### Unicode Table
```
╔══════════════════════════════════╦═════════╦════════════════════════╗
║               Col1               ║  Col2   ║          Col3          ║
╠══════════════════════════════════╬═════════╬════════════════════════╣
║ Value 1                          ║ Value 2 ║ 123                    ║
║ Separate                         ║ columns ║ with a tab or 4 spaces ║
║ This is a row with only one cell ║         ║                        ║
╚══════════════════════════════════╩═════════╩════════════════════════╝
```

### Github Markdown table
```
|               Col1               |  Col2   |          Col3          |
|----------------------------------|---------|------------------------|
| Value 1                          | Value 2 | 123                    |
| Separate                         | columns | with a tab or 4 spaces |
| This is a row with only one cell |         |                        |
```

### Re StructuredText table
```
 ================================== ========= ======================== 
                Col1                  Col2              Col3           
 ================================== ========= ======================== 
  Value 1                            Value 2   123                     
  Separate                           cols      with a tab or 4 spaces  
  This is a row with only one cell                                     
 ================================== ========= ======================== 
```
### Also possible to generate table in `html` format.



