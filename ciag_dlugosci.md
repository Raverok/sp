```c
dolna=0; gorna=0; suma=a[0]; /* suma=a[dolna]+a[dolna+1]+...+a[gorna] */
while( gorna<n && suma !=r)
if(suma<r) { gorna=gorna+1; suma=suma+a[gorna]; }
else { suma = suma-a[dolna]; dolna=dolna+1;}
```
```c
Wstawiwanie a[k] do uporzadkowanego juz ciagu
a[0],a[1],...,a[k-1];
i=k;
while(i>0 && a[i-1]>a[i]){
zamienic a[i-1] z a[i]
i=i-1;
}
```
