# OSSP_hw_2
```C
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

void main()
{
	char cName[20];
    char cTeamName[20];
	int iStudentNum;

	printf("이름을 입력하시오: ");
	scanf("%s", &cName);
	printf("학번을 입력하시오: ");
	scanf("%d", &iStudentNum);
    printf("팀 이름을 입력하시오: ");
	scanf("%s", &cTeamName);

	printf("\n<출력>\n");
	printf("이름: %s \n", cName);
	printf("학번: %d \n", iStudentNum);
    printf("팀 이름: %s\n", cTeamName);

	return 0;
}
