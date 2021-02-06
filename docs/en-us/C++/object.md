# C++ Object
This is an introduction to the object of C++ and will not appear in the directory on the left

## Write HelloWorld object
```c++
#include<iostream> 
using namespace std;

class Hello
{
public:
	void print() {
		cout << "Hello, World!";
	}
};

int main()
{
	Hello hello;
	hello.print();
	return 0;
}

```
