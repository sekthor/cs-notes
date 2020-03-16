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
