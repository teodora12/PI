# PINF - Poslovna informatika

Projektovanje i implementacija podsistema za fakturisanje

Projekat je radjen uz pomoc Mendix platforme, omogucava da se izvsi proces prodaje. Kupac narucuje ponudjenu
robu ili uslugu, prodavcu stize formirana narudzbenica pa onda on na osnovu toga generise izlaznu fakturu i 
racun-otpremnicu u PDF formatu.
Projekat je radjen u timu koji je sadrzao 2 clana.

Projekat mozete pogledati na sledecem linku: https://prodajatim18-sandbox.mxapps.io/index.html?profile=Responsive
korisnicka imena i lozinke koje se koriste:

username: demo_shop; password: AR6BJR9i5j      -> prodavac, kreira proizvode i generise fakture i otpremnice (kartica narucivanje -> narudzbenica -> izabere se jedna -> napravi fakturu, zatim kartica faktura -> izabere se jedna -> pa se izabere stampanje PDF dokumenta)
username: demo_administrator; password: pJLvPBup45       -> admin, upravlja korisnicima u sistemu
username: demo_user; password: xVOpNfUO70      -> kupac, narucuje robu (kartica narucivanje -> naruci -> kreira se narudzbenica)

neka bitna ogranicenja: 
• datum fakture ne sme biti veci od tekuceg datuma
• datum valute ne sme biti manji od datuma fakture
