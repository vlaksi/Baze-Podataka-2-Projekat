# Baze2-Projekat

<details>
  <summary> Primer specifikacija </summary> <br>
  
## Tektulna specifikacija

  - tekstualna specifikacijasistema koja treba da lici na zadatke iz er modela 
  - ta specifkacija nema pravilo koliko duga mora da bude, od pola jedne do stranu, dve
  
![image](https://user-images.githubusercontent.com/45834270/103241837-b2285400-4954-11eb-83b1-b4264c9462d6.png)

![image](https://user-images.githubusercontent.com/45834270/103242300-0da71180-4956-11eb-9edc-417bf37604a4.png)

![image](https://user-images.githubusercontent.com/45834270/103242390-4cd56280-4956-11eb-8cdf-08b698c50827.png)

![image](https://user-images.githubusercontent.com/45834270/103241964-03d0de80-4955-11eb-8c32-4287ca0b2efb.png)

![image](https://user-images.githubusercontent.com/45834270/103241973-0af7ec80-4955-11eb-8337-6c415cd6e7e0.png)

## Specifikacija relacionog modela

  - iz ER modela prevodjenje u relacioni model 

![image](https://user-images.githubusercontent.com/45834270/103241982-11866400-4955-11eb-8422-7d431d8a729e.png)

  
<br>

</details>


<details>
  <summary> Klasicne greske kod pravljenja ER mdoela </summary> <br>

Ono sto kasnije nema smisla zbog prevodjenja 
  
  - i sa donje i sa gornje strane je minimalni kardinalitet 1 
  - imamo entitet sa samo jednim atributom i onda imamo neki strani kljuc ka tom entitetu 
  
</details>


<details>
  <summary> Korisne reference </summary> <br>
  
  - softver za kreiranje diagrama: https://app.diagrams.net/
  
  <br>
  
</details>


<details>
  <summary> Automatsko prevodjenje ER modela u relacioni model </summary> <br>

  - u data modeleru napravimo ER model kao sto smo u specifikaciji to ucinili 
  - izgenerisemo DDL skripte 
  - napravimo korisnicku semu kao na BP1 , pokrenemo te skripte kako bi se izgnerisale tabele
  - popunimo te tabele nekim podacima 
  - napravimo jedan, dva slozenija SQL upita (bilo koji upit koji u sebi ima neki spoj, neko grupisanje, neku agregacionu f-ju)(ne mora imati nezavisne ugnjezdene upite, zavisne ugnjezdene upite, rekurziju, neke poglede..)
    - kada kreiramo taj upit, on treba da odgovara na neko smisleno pitanje u nasem informacionom sistemu 
  
</details>

