<div align="center">

## Basic Calculator


</div>

### Description

Basic calculator with switch-case
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kaan KAMIS](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kaan-kamis.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kaan-kamis-basic-calculator__3-13354/archive/master.zip)





### Source Code

```
/*
*	Basic calculator with switch-case
*	Mustafa Kaan KAMIS
*	http://www.k2an.com
*/
#include <stdio.h>
int main(void)
{
   char kaankamis; // operators (+,-,*,/)
	 int sayi1,sayi2,toplam; // number1, operator, number2
	 printf("Enter Numbers and Operator : \n");
	 printf("Example : 2 * 4 \n");
	 scanf("%d %c %d",&sayi1,&kaankamis,&sayi2);
   switch (kaankamis)
   {
    case '+':
     toplam = sayi1 + sayi2;
     break;
    case '-':
     toplam = sayi1 - sayi2;
     break;
	  case '*':
     toplam = sayi1 * sayi2;
     break;
	  case '/':
     toplam = sayi1 / sayi2;
     break;
    default:
     printf("Wrong operator please use following operators +,-,*,/ \n");
		 break;
   }
		printf("Result of %d %c %d is : %d\n",sayi1,kaankamis,sayi2,toplam);
return(0);
}
```

