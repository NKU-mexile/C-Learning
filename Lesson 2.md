# C++ 第二课
### C++程序组成
- 语句
```c++
#include<iostream>//预处理命令语句
using namespace std;
int main()//函数定义语句
{
    int a,b;//声明语句
    cout<<"a=";//输出语句
    cin>>a;//输入语句
    cout<<"b=";
    cin>>b;
    int c = a+b;//声明+赋值语句
    cout<<"a+b="<<c<<endl;
    return 0;
}
```
### 初识C++程序
- 注释
  - `//`
  - `/*`和`*/`
- 文件嵌入命令
  - `#include`
  - 将`<>`中的指定文件嵌入命令所在位置
- 主函数
  - `void main(){}`
- 输出语句
  - `cout`
  - 标准输出流对象

### 输入/输出语句
- C语言的输入输出函数
  - 头文件`stdio.h`
  - 标准输入函数`scanf`
    - `scanf('%d",&a);`
    - `cin>>a;`
  - 标准输出函数`printf`
  - `printf("Let's learn to write a C++ program.");`
  - `cout<< "Let's learn to write a C++ program.";`
