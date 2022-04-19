**WORKING ON THE PRINTF, WILL THEY WORK!**
---

**Description**
---
This team project is part of the first year curriculum of ALX. _printf replicates the C standard library printf() function.<br>


+ How to use git in a team setting<br>
+ Applying variadic functions to a big project<br>
+ The complexities of printf<br>
+ Managing a lot of files and finding a good workflow<br>


**Prototype**
---
```int _printf(const char *format, ...);```

**Usage**<br>
---
+ Prints a string to the standard output, according to a given format<br>
+ Returns the number of characters in the output string on success, -1 otherwise<br>
+ Call it this way: _printf("format string", arguments...) where format string can contain conversion specifiers and flags, along with regular characters<br>

**Examples**<br>
---
+ ```_printf("Hello, ALX\n")``` prints "Hello, ALX", followed by a new line<br>
+ ```_printf("%s", "Hello")``` prints "Hello"<br>
+ ```_printf("This is a number: %d", 98)``` prints "This is a number: 98"
Tasks<br>
These are all the tasks of this project, the ones that are completed link to the corresponding files.<br>

[0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life](https:/RachaelKivuti
/github.com//printf/blob/master/_printf.c)<br>
---
Write a function that produces output according to format.<br>
c : converts input into a character<br>
s : converts input into a string<br>
1. Education is when you read the fine print. Experience is what you get if you don't
Handle the following conversion specifiers:<br>
d : converts input into a base 10 integer<br>
i : converts input into an integer<br>
2. Just because it's in print doesn't mean it's the gospel<br>
Create a man page for your function<br>
3. With a face like mine, I do better in print
Handle the following conversion specifiers:<br>
b : the unsigned int argument is converted to binary<br>
4. What one has not experienced, one will never understand in print<br>
Handle the following conversion specifiers:<br>
u : converts the input into an unsigned integer<br>
o : converts the input into an octal number<br>
x : converts the input into a hexadecimal number<br>
X : converts the input into a hexadecimal number with capital letters<br>
5. Nothing in fine print is ever good news<br>
Use a local buffer of 1024 chars in order to call write as little as possible.<br>
6. My weakness is wearing too much leopard print<br>
Handle the following custom conversion specifier:<br>
S : prints the string<br>
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)<br>
7. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print<br>
Handle the following conversion specifier:<br>
p : int input is converted to a pointer address<br>
8. The big print gives and the small print takes away<br>
Handle the following flag characters for non-custom conversion specifiers:<br>
+ : adds a + in front of signed positive numbers and a - in front of signed negative numbers<br>
space : same as +, but adds a space (is overwritten by +)<br>
adds a 0 in front of octal conversions that don't begin with one, and a 0x or 0X for x or X conversions<br>
---
**[9. Sarcasm is lost in print]**<br>
Handle the following length modifiers for non-custom conversion specifiers:<br>
l : converts d, i, u, o, x, X conversions in short signed or unsigned ints<br>
h : converts d, i, u, o, x, X conversions in long signed or unsigned ints<br>
**[10. Print some money and give it to us for the rain forests]**<br>
Handle the field width for non-custom conversion specifiers.<br>
**[11. The negative is the equivalent of the composer's score, and the print the performance]**<br>
+ Handle the precision for non-custom conversion specifiers.<br>
**[12. It's depressing when you're still around and your albums are out of print]**<br>
+ Handle the 0 flag character for non-custom conversion specifiers.<br>
**[13. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection]**<br>
+ Handle the - flag character for non-custom conversion specifiers.<br>
14. Print is the sharpest and the strongest weapon of our party<br>
+ Handle the following custom conversion specifier:<br>
r : prints the reversed string<br>
15. The flood of print has turned reading into a process of gulping rather than savoring<br>
+ Handle the following custom conversion specifier:<br>
R : prints the rot13'ed string<br>

All the above options work well together.<br>
