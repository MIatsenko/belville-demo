# Predlog veb-sajta — Belville Dental Centar

Demo (predlog) nove početne strane za stomatološku ordinaciju **Belville Dental Centar**,
Jurija Gagarina 14N/lokal 2, Novi Beograd.

Stranica je napravljena na materijalima ordinacije — fotografije ordinacije i lekara, tekstovi
o uslugama, radno vreme i kontakt podaci preuzeti su sa javnog sajta belvilledental.com.
Ovo nije zvaničan sajt ordinacije i nije javna ponuda: prikazuje kako bi početna strana mogla
da izgleda, pre bilo kakvog dogovora.

## Šta sadrži

- prvi ekran sa fotografijom ordinacije i pozivom na zakazivanje pozivom na telefon;
- traka sa činjenicama: godina osnivanja, broj lekara, oblasti lečenja, radno vreme;
- deset oblasti lečenja, od preventive i dečije stomatologije do implantologije i ortodoncije;
- tim od osam lekara sa fotografijama i specijalnostima;
- galerija ordinacije;
- kontakt blok sa radnim vremenom, adresom i linkom na mapu.

## Tehnički

Jedna statička stranica (`index.html`), bez eksternih biblioteka i bez mrežnih zahteva ka
trećim servisima. Prilagođena telefonu, tabletu i desktopu. `<meta name="robots" content="noindex">`.

Generisano iz šablona `demo_build.py` (jedna HTML stranica + `config.json` u izvornom projektu).
