# first-own-code
ASCII dislay
#include <stdio.h>

main(void)
{
	char a;
	
	a = 0;
	while ( 127 > a > 0) {
		printf("%c:%d\t", a,a);
		++a;
	}
	
	system("pause");
}
