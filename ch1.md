# 输入输出

`c++` 使用`cin`和`cout`来输入输出，此时，要`include` 头文件`iostream`
```c++
#include <iostream>

using namespace std;

int main() {
   cout << 2+4 << " " << 10;
   std::cout << "Hello, World!" << std::endl;
   int X = 0;
   int a = 0;
   cin >> X >> a;
   cout << X << "\t" << a;
   cout << "Hello World!";
   return 0;
}


```
当然，`c++`也支持使用`scanf`和`printf`进行输入输出,相应的，此时就应该使用`cstdio`头文件
```c++
#include <cstdio>

using namespace std;

int main() {
    int a = 0;
    int b = scanf("%d",&a); // scanf()的返回值也是有意义的
    printf("%d\t%d\n",a,b);
    return 0;
}

```