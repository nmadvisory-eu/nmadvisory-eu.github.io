# Sito opint.eu

Sito statico generato con Hugo e pubblicato con GitHub Pages. Ogni modifica salvata sul ramo `main` ripubblica il sito in circa un minuto.

## Dove sono i testi

- Una pagina = un file in `content/`, in italiano (`.it.md`) e in inglese (`.en.md`)
- La home è in `content/_index.it.md` e `content/_index.en.md`: i testi stanno nell'intestazione del file, tra le due righe `---`
- Le sei tipologie sono in `content/trasformazione-crescita/`

## Che cosa non toccare modificando un testo

- Nell'intestazione: le voci `chiave`, `translationKey`, `url`, `percorso`
- Nel testo: i comandi tra `{{< ... >}}`, che creano riquadri, elenchi con spunte, fasi ed esperienze

## Altro

- Dati legali, email e LinkedIn: `hugo.toml`, sezione `[params]`
- Grafica: `assets/css/opint.css`
- Foto e logo: `static/img/`
- Caratteri Archivo e Public Sans (licenza SIL Open Font License): `static/fonts/`
- Icone Phosphor (licenza MIT): `assets/icone/`
