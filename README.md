
#include <stdlib.h>
#include <stdio.h>
#define _CRT_SECURE_NO_WARNINGS

// int is used when when you want to return a value.
// void is used when u want to return a something else.

void check(int num1, int num2)
{
	if (num1 == num2)
		printf("Eror: The same numbers.");
	if (num1 * 2 == num2)
		printf("%d is two times bigger.\n", num2);

	if (num2 * 2 == num1)
		printf("%d is two times bigger.\n", num1);
	else
		printf("Error: Unknown.");
}

void main()
{
	int x, y;
	printf("please enter 2 numbers for a check up!\n");
	scanf_s("%d %d", &x, &y);
	check(x, y);
	system("pause");
}

//יש לכתוב תוכנית אשר מפעילה פונקציה שמקבלת 2 מספרים 
//ומדפיסה אם האיבר השני גדול פי 2 מהאיבר הראשון או לא
