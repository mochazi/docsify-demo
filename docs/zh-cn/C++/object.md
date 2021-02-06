# C++对象
这是一段关于C++对象介绍，并不会出现在左边的目录

## 编写HelloWorld对象
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
