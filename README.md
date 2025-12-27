# Indexo uz YNAB CSV Konvertētājs

Vienkāršs un drošs rīks, kas ļauj konvertēt **AS INDEXO Banka** sagatavotos PDF bankas izrakstus uz **YNAB** (You Need A Budget) piemērotu CSV formātu.

## Kāpēc izmantot šo rīku?

* **Privātums:** Fails netiek augšupielādēts nevienā serverī. Visa apstrāde notiek lokāli jūsu pārlūkprogrammā, izmantojot JavaScript.
* **Ātrums:** Nav nepieciešama reģistrācija vai instalācija.
* **Precizitāte:** Rīks automātiski atpazīst darījuma datumu, saņēmēju (Payee), aprakstu (Memo) un summu.

## Kā lietot?

1.  Lejupielādējiet savu bankas izrakstu no Indexo lietotnes PDF formātā.
2.  Atveriet šo rīku (izmantojot GitHub Pages saiti vai lejupielādējot `index.html` failu).
3.  Ievelciet (Drag & Drop) savu PDF failu norādītajā laukumā vai izvēlieties to no sava datora.
4.  Pārbaudiet darījumu priekšskatījumu.
5.  Spiediet pogu **"Lejupielādēt CSV priekš YNAB"**.
6.  YNAB programmā/vietnē izvēlieties savu bankas kontu un veiciet **Import**, izvēloties tikko lejupielādēto CSV failu.

## Tehnoloģijas

* [PDF.js](https://mozilla.github.io/pdf.js/) — PDF datu nolasīšanai.
* [Tailwind CSS](https://tailwindcss.com/) — modernam un responsīvam dizainam.
* Tīrs JavaScript — datu apstrādei un CSV ģenerēšanai.

## GitHub Pages publicēšana

Lai šis rīks būtu pieejams tiešsaistē:
1.  Pārliecinieties, ka galvenais fails ir nosaukts par `index.html`.
2.  Augšupielādējiet to savā GitHub repozitorijā.
3.  Dodieties uz **Settings** -> **Pages**.
4.  Sadaļā **Build and deployment** izvēlieties `Branch: main`.
5.  Pēc brīža jūsu lapa būs pieejama `https://<lietotājvārds>.github.io/<repo-nosaukums>/`.

---
*Šis ir atvērtā pirmkoda projekts un nav oficiāli saistīts ar AS INDEXO Banka vai YNAB.*
