# C lanuage

## Pointers

While a variable stores a cretain value at a certain point in memory. A pointer
stores the address of that point in memory. It "points" to a value in memory.

To create a variable storing a pointer, use the asterisk character, before the
variable name. The data type should be the same of whatever value the pointer
points to.

```c
int *ptr;
```

To acess a variables memory adress the ampercent character can be used. In the
example we store the address of ```x``` in pointer ```ptr```.

```c
int *ptr = &x;
```

Whenever we want to acess the value of what the pointer points to, we can use
the asterisk again. So now that we have the value ```7``` in variable ```x``` and
```ptr``` pointing to that location, we can access the value ```7``` like so:

```c
*ptr = 6;
```

A full example looks like this:

```c
int main()
{
    // variable x is assigned the value of 7
    int x = 7;

    // * indicates a pointer, in this case to an int
    int *ptr;

    // to acces the memory address of a variable use the &
    ptr = &x;
}
```
