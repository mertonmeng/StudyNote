## C# Study Note ##

**Precision Calculation**

"double" is not precise enough. Use "decimal" to get more precise result.

**Round to zero situation**

Math.Round function still retains the sign after rounding to zero.

**Divide by zero situation**

non-zero number / - 0.0 = -Infinity  
non-zero number / 0.0 = Infinity