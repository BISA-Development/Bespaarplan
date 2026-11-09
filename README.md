# Greenteam Bespaarplan

Webtool waarmee adviseurs een persoonlijk bespaarplan als PDF maken:
De Gouden Drie, Thuisbatterij of Warmtepomp.

- Alles draait in de browser van de adviseur. Er worden geen klantgegevens verstuurd of opgeslagen op een server.
- De gegevens van de adviseur (naam, e-mail, telefoon) worden onthouden in de eigen browser.

Directe links naar een soort plan:
- `.../#gouden-drie`
- `.../#thuisbatterij`
- `.../#warmtepomp`

## Online zetten met GitHub Pages
1. Maak op github.com een nieuwe repository, bijvoorbeeld `bespaarplan` (Public).
2. Kies **Add file → Upload files** en sleep `index.html`, `README.md` en de map `lib` erin. Klik **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Source* **Deploy from a branch**, branch **main**, map **/ (root)**, en klik **Save**.
4. Na een minuut staat de tool op `https://<jouw-gebruikersnaam>.github.io/bespaarplan/`.
