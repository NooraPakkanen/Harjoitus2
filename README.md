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


<img width="745" alt="Screenshot 2023-02-01 at 1 58 43" src="https://user-images.githubusercontent.com/122889266/215922217-546670e0-270c-439c-bf14-0fd7b9980116.png">

<img width="621" alt="Screenshot 2023-02-01 at 2 12 20" src="https://user-images.githubusercontent.com/122889266/215925740-e679e221-b0d1-4ed6-9880-4337dce43eea.png">

FHS





Root

Juurihakemisto.  Linux/Unix -järjestelmissä tiedostohierarkian ylimpänä. Juurihakemistoa merkitään kauttaviivalla (/). 



Home

Home hakemistosta löytyy kaikkien käyttäjien kotihakemistot

<img width="382" alt="Screenshot 2023-02-01 at 3 39 08" src="https://user-images.githubusercontent.com/122889266/215925305-1e70c7c2-fd76-429a-be87-071550eedff1.png">



Home/noora

Käyttäjän Noora kotihakemistossa on käyttäjän tallentamat tiedostot

<img width="710" alt="Screenshot 2023-02-01 at 3 38 22" src="https://user-images.githubusercontent.com/122889266/215925195-0d505639-857e-48ae-a31a-047a4a2d0cc7.png">


Etc-kansio sisältää järjestelmän asetustiedostoja. Kaikki kansion tiedostot ovat tekstitiedostoja.

<img width="787" alt="Screenshot 2023-02-01 at 3 40 06" src="https://user-images.githubusercontent.com/122889266/215925376-e991de5e-6f2c-4799-aac4-5c2a4bb0a048.png">

Media

 Siirrettävän median tiedostoja
 
 <img width="360" alt="Screenshot 2023-02-01 at 3 42 41" src="https://user-images.githubusercontent.com/122889266/215925460-d714310b-66a0-4960-b1e7-91e639be4d56.png">


Var/log 

Sisältää muuttuvia tiedostoja kuten esimerkiksi lokitiedostoja.


<img width="759" alt="Screenshot 2023-02-01 at 3 43 58" src="https://user-images.githubusercontent.com/122889266/215925544-3175dea4-3e53-43e1-a623-8352a13e9048.png">



Grep

Grep-komennon avulla voidaan etsiä tietoa tiedostoista. Loin tätä tehtävää varten esimerkkitiedoston testi1.txt kansioon testi. Etsin tästä tiedostosta tietoa grep-komennolla. 

Grep komennolla voidaan etsiä numeroita tekstitiedostosta. Tuloksena saadaan kaikki rivit, jossa haluttu numero esiintyy. Alla kuva käyttämästäni komennosta ja tuloksesta. 

<img width="632" alt="Screenshot 2023-02-01 at 3 28 48" src="https://user-images.githubusercontent.com/122889266/215922740-ebdabc76-37f8-46e8-9811-604dddcc6337.png">



Grep komennolla voi myös etsiä sanoja. Etsin tiedostosta testi1.txt sanaa sää ja tulokseksi sain kaikki rivit, jotka sisältävät sanan sää. Alla tarkemmin käyttämäni komento ja tulostus. 

<img width="634" alt="Screenshot 2023-02-01 at 3 28 57" src="https://user-images.githubusercontent.com/122889266/215922718-939e8b70-156b-4b03-baaf-e1bcde7080b4.png">

Etsin vielä yhtä tiettyä kirjainta (l) tekstitiedostosta. Alla kuvassa on esitetty käyttämäni komento ja tulostus. Tulostus sisältää kaikki rivit, joissa esiintyy kirjain l. 

<img width="635" alt="Screenshot 2023-02-01 at 3 29 06" src="https://user-images.githubusercontent.com/122889266/215922701-0814b4da-f7e1-48f3-a9d0-b787d459a9c3.png">



