# i18XX-localisation
## Käännöstiedostot: Survey Party &amp; Gauge

Toimintaohjeet uuden kielen lisäämiseksi:

1. Luo oma haara ja paikallinen työkopio tästä tietovarastosta: https://guides.github.com/activities/forking/

2. Tee paikallisen kopion ("Clone your fork") sisältämästä `en.lproj`-hakemistosta kopio ja nimeä se kohdekielen mukaan, esim. `sv.lproj`=ruotsi

3. Korvaa uudessa `{sv}.lproj`-hakemistossa sijaitsevissa `.strings`-päätteisissä tiedostoissa lainausmerkkien sisällä olevat englanninkieliset ilmaisut kohde- (esim. ruotsin-) kielisillä - säilytä muu teksti sellaisenaan:
  ```
    en.lproj/Engine.strings: "%d–%d pelaajaa" = "%1$d–%2$d players";
    
    sv.lproj/Engine.strings: "%d–%d pelaajaa" = "%1$d–%2$d spelare";
  ``` 
  
4. Toimita muokattu paikallinen kopio "pull request"-muotoon em. ohjeiden mukaan ja lähetä tähän tietovarastoon.

---
## Translated strings for Survey Party &amp; Gauge

How to add support for a new language:

1. Fork and clone this repository: https://guides.github.com/activities/forking/

2. Within your working copy ("Clone your fork"), duplicate `en.lproj` and name it according to your target language, e.g. `fr.lproj` for French

3. For each file ending in `.strings` within the new `{fr}.lproj` directory, replace each quoted sentence in English with the equivalent in your target (e.g. French) language - leaving anything else as-is:
  ```
    en.lproj/Engine.strings: "%d–%d pelaajaa" = "%1$d–%2$d players";
    
    fr.lproj/Engine.strings: "%d–%d pelaajaa" = "%1$d–%2$d joueurs";
  ```
  
4. Submit a pull request, as described in the instructions above, against this repository.
