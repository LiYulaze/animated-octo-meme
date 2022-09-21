#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<string.h>

//enum Sex {
//	//这种枚举类型的变量的未来可能取值
//	MALE,FEMALE,
//	SECRET 
//};
//
//
//int main() {
//
//	//4.枚举常量
//	//可以被一一列举的常量
//	enum Sex s = MALE;
//	printf("%d\n", MALE);
//	printf("%d\n", FEMALE);
//	printf("%d\n", SECRET);
//	
//
//	return 0;
//}


//字符串-一串字符-用双引号引起来的一串字符
//字符串的结束标志是一个\0的转义字符

/*int main() {
	//字符数组-数组是一组相同类型的元素
	//字符串在结尾的位置隐藏了一个\0的字符
	//char arr[] = "hello";
	char arr1[] = "abc";
	char arr2[] = {'a','b','c','\0'};

	//求一下字符串的长度
	printf("%d\n", strlen(arr1));
	printf("%d\n", strlen(arr2 ));

	//int len =strlen("abc");//string length
	//printf("%d\n", len);//\0不计入长度
	
	//打印字符串
	/*printf("%s\n", arr1);
	printf("%s\n", arr2);*/

//	return 0;
//}

//int main(){
//	//转义字符-转变了原来的意思
//	//printf("c:\\test\\test.c");
//	//printf("ab\ncd");
//	//printf("%c\n", '\'');
//	//printf("%s\n", "\"");%d-整型，%c-字符，%s-字符串
//	//printf("\a\a\a\a");
//
//	return 0;
//}

//int main() {
//	//printf("%c\n", '\130');//8进制的130是十进制的88  
//	////X的ASCII码值是88
//	//printf("%c\n", '\101');//A-65-8进制是101
//	//printf("%d\n", '\A');
//	//printf("%c\n", '\x30');
//	printf("%d\n", strlen("c:\test\328\test.c"));
//
//	return 0;
//}
