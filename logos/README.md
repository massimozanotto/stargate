# Logos

Inserire qui i file SVG o PNG dei loghi universitari.

## Convenzione nomi file

Il nome del file deve corrispondere al campo `id` di ogni camera in `CAMERAS[]` (tutto minuscolo):

| File           | Università                      |
|----------------|---------------------------------|
| `uda.svg`      | Università D'Annunzio (host)    |
| `parigi.svg`   | Université Paris Cité           |
| `madrid.svg`   | Universidad Complutense         |
| `stoccolma.svg`| Stockholm University            |
| `berlino.svg`  | Freie Universität Berlin        |
| `praga.svg`    | Charles University              |
| `lisbona.svg`  | Universidade de Lisboa          |
| `zurigo.svg`   | Universität Zürich              |
| `londra.svg`   | University College London       |
| `dublino.svg`  | University College Dublin       |

Se il file non è presente, viene mostrata automaticamente l'abbreviazione testuale (es. `PAR`, `MAD`).

Per usare un percorso personalizzato, aggiungere il campo `logo` nella config CAMERAS:
```js
{ id: 'parigi', label: '...', url: '...', logo: 'logos/paris-cite.png' }
```
