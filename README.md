# Opintojen ja tehtävien seuranta

Tämä on Ohjelmointivälineet ja versionhallinta -kurssin lopputyö.

Projektissa seuraan kursseja ja opiskelutehtäviä tekstitiedostojen avulla.
Harjoittelen samalla Gitin ja GitHubin käyttöä, haaroja,
muutosten yhdistämistä ja versionhallinnan muita toimintoja.

## Projektin tiedostot

- kurssit.md: seurattavat kurssit ja niiden tilanne.
- tehtavat.md: opiskelutehtävien seuranta.
- vinkit.md: opiskelua helpottavia vinkkejä.
- .gitignore: jättää lokitiedostot versionhallinnan ulkopuolelle.

## Käytetyt Git-komennot

Kloonasin projektin SSH-yhteydellä ja tallensin muutokset add- ja commit-komennoilla. Käytin pushia ja pullia GitHubin kanssa. Harjoittelin haaroja komennoilla switch, merge ja rebase sekä muutosten käsittelyä komennoilla stash, stash pop, revert ja cherry-pick. Tein myös Pull Requestin ja yhdistin sen GitHubissa.

## Ongelmat ja niiden ratkaisut

Merge-konflikti syntyi, kun muutin samaa otsikkoa kahdessa haarassa. Ratkaisin sen valitsemalla VS Codessa Accept Incoming Change. Lokitiedoston ohitus alkoi toimia .gitignoren tallentamisen jälkeen. Varmistin toiminnan komennolla git check-ignore -v testi.log.

## Mitä opin

Opin tallentamaan muutoksia Gitin historiaan ja käyttämään haaroja. Harjoittelin myös konfliktin ratkaisemista ja virheellisen commitin kumoamista. Tarvitsin vielä ohjeita erityisesti edistyneissä komennoissa.