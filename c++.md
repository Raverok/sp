```c
liczba cyfr liczby a: dlug_a
liczba cyfr liczby b: dlug_b
if(dlug_a<dlug_b) max=dlug_b;
else max=dlug_a;
int a[max+1],b[max+1], wynik[max+1];
/* wczytywanie a */
for(i=max;i>=dlug_a;i=i-1) a[i]=0;
for(i=dlug_a-1;i>0;i=i-1) scanf("%i",&a[i]);
/* wczytywanie b */
-----||-------
/* dodawanie */
przen=0;
for(i=0;i<=max;i=i+1) {
wynik[i]=a[i]+b[i]+p;
if(wynik[i]>=10) {p=1; wynik[i]=wynik[i]-10;}
else p=0;
/* drukowanie */
i=max;
while(i>=0 && wynik[i]==0)
i=i-1;
if(i<0) printf('0');
else
while(i>=0) {
pintf("&i", wynik[i]);
i=i-1;
}
```
