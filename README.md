# 参考书目

数据结构（C语言版本）严蔚敏 吴伟民 编著

[视频](https://www.bilibili.com/video/BV1db411Y7Lm?spm_id_from=333.1007.top_right_bar_window_default_collection.content.click)

# 算法简要说明

(1)预定义常量和类型

``` c
// 函数结果状态代码
#define	TRUE		1
#define	FALSE		0
#define	OK			1
#define	ERROR		0
#define INFEASIBLE	-1
#define	OVERFLOW	-2
// Status是函数的类型, 其值是函数结果状态代码
typedef int Status;
```

(2)数据结构的表示(存储结构)用类型定义(**typedef**)描述. 数据元素类型约定为ElemType, 由用户在使用该数据类型时自行定义. 

(3)当函数返回值为**函数结果状态代码**时, 函数定义为**Status**类型. 为了便于算法描述, 除了值调用方式外, 增添了C++语言的引用调用的参数传递方式. 在形参表中, 以**&**打头的参数即为引用参数. 

# 其他说明

笔记中有些语法在GitHub中无法正确显示, 所以添加了html文件便于浏览; 

部分笔记记录在课本上, 该笔记主要为了加深对于算法的认识以及GitHub的使用, 所以算法占主要部分, 学习时要配合课本使用; 