# Aihemäärittely


**Aihe:** Miinaharava on yksinpelattava peli, jonka ideana on löytää kaikki ruudukkoon kätketyt miinat mahdollisimman nopeasti. Klikkaa hiiren vasemmalla näppäimellä paljastamattomia ruutuja: jos ruudussa on miina, se räjähtää ja peli päättyy. Jos ruudussa ei ole miinaa, ruudussa näkyy, monessako ruudun kahdeksasta naapuriruudusta on miina. 

Mikäli klikatun ruudun yhdessäkään naapuriruudussa ei ole miinaa, peli paljastaa ensin kaikki siihen yhteydessä olevat ruudut, joiden naapurissa ei myöskään ole miinaa, sekä lisäksi tämän paljastetun alueen reunalla olevat ruudut, joiden naapurissa on miina. Tämä ei helpota mutta nopeuttaa peliä etenkin suurella laudalla, jossa on vähän miinoja, koska "nollaruutuja" ei tarvitse klikkailla yksitellen. 

Oikealla näppäimellä (Flash-versiossa käytä näppäimistön välilyöntiä!) pelaaja voi merkitä lipulla paljastamattoman ruudun, jossa päättelee olevan miinan. Kun kaikki miinattomat ruudut on paljastettu, pelaaja on onnistunut ja hänen tuloksensa on käytetty aika. 


**Käyttäjät:** Pelaaja

**Pelaajan toiminnot:**
- Paljastamattomien ruutujen valitseminen
- Ruudun merkitseminen miinan sisältäväksi

