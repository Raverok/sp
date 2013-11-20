```c
dolna=0; gorna=0; suma=a[0]; /* suma=a[dolna]+a[dolna+1]+...+a[gorna] */
while( gorna<n && suma !=r)
if(suma<r) { gorna=gorna+1; suma=suma+a[gorna]; }
else { suma = suma-a[dolna]; dolna=dolna+1;}
```
