/*  
    Dobaviti prikaz laksih staza (one koje nisu crne) i
    prikazati duzinu te staze, da li je staza otvorena i
    br telefona gorske sluzbe koja je odrzava
*/
select staza.idstz, staza.tipstz, staza.duzstz, staza.otvstz, gorskasluzba.brtelgsl
from staza,gorskasluzba
where staza.gorskasluzba_idgsl = gorskasluzba.idgsl
and staza.tipstz != 'crna';


/*
    Prikazati tip staze i za svaki od tipa staze
    prikazati koliko je najduza staza tog tipa
    najkraca kao i kolika je prosecna duzina staze tog tipa.
*/
select tipstz, max(duzstz) "Najvise km", avg(duzstz) " Prosecno km", min(duzstz) "Najmanje km"
from staza
group by tipstz;

