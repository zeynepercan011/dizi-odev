# dizi-odev

//5 ogrenci icin final ve vize puani al ayri ayri dizilerde tut. ortalama hesaplayan fonks ve bu fonksiyon diziye atilacak.main fonksda vize final ort gostersin.
//dizi nasil return edilir?

#include<stdio.h>

int vizeortalama(int ortBul[]);
int finalortalama(int ortBul1[]);

int main(void)
{
int i;
int vize[i];
int final[i];
int ortBul,ortBul1;
int yazdir,yazdirr;

for(int i=0;i<5;i++)
{
	printf("%d. ogrenci icin vize notunu giriniz:\n" , i+1);
	scanf("%d" , &vize[i]);
}

for(int i=0;i<5;i++)
{
	printf("%d. ogrenci icin final notunu giriniz:\n" , i+1);
	scanf("%d" , &final[i]);
}

printf("vize ortalamasi: %d \n" , ortBul);
printf("final ortalamasi: %d \n" , ortBul1);

return 0;

}

int vizeortalama(int ortBul[])
{
	int sum;
	
	for(int i=0;i<5;i++)
	{
		sum+=ortBul[i];
	}
	
	int ortalama=sum/5;
	
	return ortalama;
}

int finalortalama(int ortBul1[])
{
	int sum;
	
	for(int i=0;i<5;i++)
	{
		sum+=ortBul1[i];
	}
	
	int ortt=sum/5;
	
	return ortt;
}
