# 2. Hello, World!

---

What to expect from C? The stairs always gonna get me up.

C is a low level language, which can directly get us in touch with the bare metal. It wont create perfect applications on its own, we have to be so explicit about all the decisions we make. scarier part is gonna be learning pointers (Author says it). C is going to have a touch of all other programming languages we have already worked on, coz everything has a touch of C.

```c
#include <stdio.h>

int main (void) {
	printf("Hello, world!\n")
}
```

### Code Explanation:

The `#` in the code tells the C preprocesser to grab the contents of the file mentioned and put it in the current codebase for some actions. so what is a C preprocessor. C preprocesser is the first thing that process our source, then it is given to the compiler, then the compiler turns the source into machine code/assembly which is rapidly understandable by the Computer CPU. this is why C runs faster than most of the modern langs.

`stdio.h` is a header file.

`main()` is a func, this is a special function which runs everytime a program is executed. whatever is inside the `{}` are called as the function definition

but we can see `printf()` being the calling of the function not the definition.

### Build C programs:

We can use `gcc` to build C programs source code to executables on our local system.

```c
gcc -o hello hello.c
```

the above piece of line in a terminal says that. we are using gcc to convert the source code `hello.c` into machine executable .exe file `hello` this can be runned by `./hello`. On a high level the whole thing that is happening around is, a piece of source code is being converted into a way that it is easily executable by the computer rapidly.
