#define _CRT_SECURE_NO_WARNINGS
//注意：有且只有一个main函数
//      1.一个工程中可以有多个.c文件
//      2.但是多个.c文件中只能有一个main函数
//      3.前面加上定义#define _CRT_SECURE_NO_WARNINGS
// 
//写代码
//1.写出主函数（main函数）
//100-500代码
//如何执行呢？-C语言是从主函数的第一行开始执行的
//所以C语言代码中得有main函数-入口
// 
//int:函数的返回类型为整型，main():函数名
// {}括起来的叫函数体
// 
//写个代码，在屏幕上打印：比特
//printf-库函数-在屏幕上打印信息的
//printf的使用的，也得打招呼(引用头文件stdio.h)

#include<stdio.h>
//int main()   
//{
//	printf("比特");
//	return 0;
//}

//编译+链接+运行代码
//快捷键：1.CTRL+F5
//        2.FN+CTRL+F5
//        3.菜单中：【调试】->【开始执行不调试】
//程序执行太快，没有看到
//为了改变，点击当前项目属性-配置属性-链接器-系统-子系统-改成控制台-应用-确定

//数据类型
//计算机语言-写程序-解决生活问题
//必须有能力来描述生活中问题！
//购物商城-上架商品，价格-15.6元-小数  1.56*10^1
//年龄-50
//C语言-浮点数
//       -整型
//a
//'a' -字符a

#include<stdio.h>
//int main()
//{
//	//字符类型
//	char ch = 'a';
//	//短整型
//	short num = 10;
//	//整型
//	int age = 10;
//	//长整型
//	long agd = 200;
//	//单精度浮点型
//    float weight = 55.5;
//	//双精度浮点型
//	double d = 0.0;
//
//	return 0;
//}

#include<stdio.h>
//int main()
//{
//	printf("比特\n");
//	printf("bite\n");
//	printf("100\n");
//	printf("%d\n",100);   //打印一个整数-%d    直接打显示输出，%d是获取逗号后面的
//	
//	printf("%d\n", sizeof(char));
//	printf("%d\n", sizeof(short));
//	printf("%d\n", sizeof(int));
//	printf("%d\n", sizeof(long));
//	printf("%d\n", sizeof(long long));
//	printf("%d\n", sizeof(float));
//	printf("%d\n", sizeof(double));
//
//	return 0;
//}
