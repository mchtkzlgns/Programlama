# Programlama
#include<stdio.h> #include<conio.h>

main() {

int islem; int bakiye=100; int miktar;

printf("1. Para Cekme\n"); printf("2. Para Yatirma\n"); printf("3. Kart Iade\n");

printf("Islem Seciniz\n"); scanf("%d",&islem);

switch(islem) {

case 1: printf("Bakiye=100 \n"); printf("cekilecek Tutar:"); scanf("%d",&miktar);

 if(miktar>bakiye)	
 {
 	printf("YETERSIZ BAKIYE\n");
 }
else{

    bakiye=bakiye-miktar;
printf("Yeni Bakiyeniz=%d\n",bakiye); }

break;

case 2:

printf("Bakiye=100\n");

printf("Yatirilacak tutar:",miktar);
scanf("%d",&miktar);
bakiye=bakiye+miktar;


printf("Yeni bakiyeniz=%d\n",bakiye);
break;

 case 3:

printf("Kartiniz iade edildi ");
break;

	getch();
	

}
}
