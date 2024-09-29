# -4-3-
#include <locale.h>
#include <stdio.h>

int main()
{
	int a, b;
	setlocale(LC_ALL, "RUS");
	puts("Введите a и b");
	scanf("%d %d", &a, &b);
	printf("________________________________________________\n");
	printf("|%+10s\t|%+10s\t|%+10s\t|\n","a+b","a*b","a-b");
	printf("________________________________________________\n");
	printf("|%+5d*%d\t|%+5d+%d\t|%+5d-%d\t|\n", a, b, a, b, a, b);
	printf("________________________________________________\n");
	printf("|%+10d\t|%+10d\t|%+10d\t|\n",a*b, a+b, a-b);
	printf("________________________________________________\n");
}
