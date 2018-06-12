# An example

This section is meant to illustrate a sample code in ABC and compare it with
equivalent code in Python and C.

## Function to convert given temperature from Fahrenheit to Celsius

In ABC language.

```ABC
HOW TO PRINT CELSIUS FROM a:
   PUT (a-32)*5/9 IN c
   WRITE a, "Fahrenheit =", 2 round c, "Celsius" /
```

The same code in Python3.

```Python
def to_celsius(a):
  c = (a-32)*5/9
  print(a + "Fahrenheit = %.2f",c + "Celsius" )
```

And in C

```C
void to_celsius(float a)
{
  c = (a-32)*5/9;
  printf("%f Fahrenheit is %.2f Celsius",a,c);
  return;
}
```

The purpose of this example is to illustrate two things: The similarity between ABC and
Python and also a glimpse of how ABC is slightly easier to code in compared to C. The second point
might not be too obvious because the example is too short to notice the differences.
