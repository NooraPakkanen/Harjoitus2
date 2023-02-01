# Harjoitus2

Micron asennus

Micro asennettiin komennolla sudo apt-get -y install micro. Asennus onnistui. 

<img width="813" alt="kuva" src="https://user-images.githubusercontent.com/122889266/215921946-935d7296-209c-4f18-bec7-6b5b7442812b.png">




Rauta

<img width="857" alt="kuva" src="https://user-images.githubusercontent.com/122889266/215921842-4ef6c734-ffe5-48d7-870f-976198239dcb.png">

 


Kuvassa näkyy paljon erilaista tietoa ja suurimmasta osasta en tiedä, että mitä ne tarkoittavat. Kuvasta kuitenkin selviää, että tietokoneessani on Intel Core i5 prosessori. Kuvassa näkyy myös muistin määrä ja järjestelmänä (system) on Virtualbox.

Apt

Asensin ohjelmat espeak ja wordgrinder. En tunne komentoriviohjelmia, joten valitsin googlailemalla muutaman ensimmäisen silmiini osuneen. Sain ainoastaan kaksi asennettua. Yritin myös muita, mutta ilmeisesti niitä ei pysty ainakaan tuota kautta asentamaan tai sitten ohjelmat olivat esimerkiksi vääriä tai vanhentuneita.


<img width="764" alt="Screenshot 2023-02-01 at 2 00 53" src="https://user-images.githubusercontent.com/122889266/215922204-8db6d230-a07a-495c-9a0f-149b68fe0787.png">
a7b0.png">

<img width="745" alt="Screenshot 2023-02-01 at 1 58 43" src="https://user-images.githubusercontent.com/122889266/215922217-546670e0-270c-439c-bf14-0fd7b9980116.png">

FHS

Root

Juurihakemisto.  Linux/Unix -järjestelmissä tiedostohierarkian ylimpänä. Juurihakemistoa merkitään kauttaviivalla (/). 

Home

Home hakemistosta löytyy kaikkien käyttäjien kotihakemistot

Home/tero

Käyttäjän Tero kotihakemistossa on käyttäjän tallentamat tiedostot

Etc-kansio sisältää järjestelmän asetustiedostoja. Kaikki kansion tiedostot ovat tekstitiedostoja.

Media

 Siirrettävän median tiedostoja

Var/log 

Sisältää muuttuvia tiedostoja kuten esimerkiksi lokitiedostoja.

Grep

Grep-komennon avulla voidaan etsiä tietoa tiedostoista. Loin tätä tehtävää varten esimerkkitiedoston testi1.txt kansioon testi. Etsin tästä tiedostosta tietoa grep-komennolla. 

Grep komennolla voidaan etsiä numeroita tekstitiedostosta. Tuloksena saadaan kaikki rivit, jossa haluttu numero esiintyy. Alla kuva käyttämästäni komennosta ja tuloksesta. 
<img width="635" alt="Screenshot 2023-02-01 at 3 29 06" src="https://user-images.githubusercontent.com/122889266/215922701-0814b4da-f7e1-48f3-a9d0-b787d459a9c3.png">

Grep komennolla voi myös etsiä sanoja. Etsin tiedostosta testi1.txt sanaa sää ja tulokseksi sain kaikki rivit, jotka sisältävät sanan sää. Alla tarkemmin käyttämäni komento ja tulostus. 

<img width="634" alt="Screenshot 2023-02-01 at 3 28 57" src="https://user-images.githubusercontent.com/122889266/215922718-939e8b70-156b-4b03-baaf-e1bcde7080b4.png">

Etsin vielä yhtä tiettyä kirjainta (l) tekstitiedostosta. Alla kuvassa on esitetty käyttämäni komento ja tulostus. Tulostus sisältää kaikki rivit, joissa esiintyy kirjain l. 


<img width="632" alt="Screenshot 2023-02-01 at 3 28 48" src="https://user-images.githubusercontent.com/122889266/215922740-ebdabc76-37f8-46e8-9811-604dddcc6337.png">
