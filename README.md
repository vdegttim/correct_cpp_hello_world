# correct_cpp_hello_world

[Correct C++](https://github.com/richelbilderbeek/correct_cpp) chapter 'Hello world'.

## Exercise

Write a Hello world program.

```
int main()
{
  // Your code here
}
```

The text should be literally `Hello world`, followed by newline.

## Running

You can run your code from Qt Creator.

Alternatively, you can call the script `build`:

```
./build
```

Example output:

```
richel@winloos:~/GitHubs/correct_cpp_hello_world$ ./build 
make -f Makefile.Release
make[1]: Entering directory '/home/richel/GitHubs/correct_cpp_hello_world'
make[1]: Nothing to be done for 'first'.
make[1]: Leaving directory '/home/richel/GitHubs/correct_cpp_hello_world'
```

## Testing

You can create a Pull request to the original GitHub.

Alternatively, you can call the script `test`:

```
./test
```

Example output:

```
richel@winloos:~/GitHubs/correct_cpp_hello_world$ ./test 
Incorrect: files are different
```

Or:

```
richel@winloos:~/GitHubs/correct_cpp_hello_world$ ./test
Correct
```
