# Dismon Pastissos i Xocolata — web gratuïta

## Publicar sense pagar
La web és estàtica i es pot allotjar amb GitHub Pages en un repositori públic i un compte GitHub Free. GitHub Pages publica fitxers HTML, CSS i JavaScript; no inclou base de dades ni pagaments.

## Abans de publicar
1. Obre `config.js`.
2. Canvia `POSA_AQUI_EL_TELEFON_AMB_PREFIX_34` pel número de WhatsApp del negoci, només xifres i amb prefix internacional. Exemple de format: `34600111222` (és només un exemple de format, no un telèfon real de Dismon).
3. Revisa les fotografies, perquè ara són imatges d'exemple externes i no fotografies pròpies verificades.
4. Revisa el catàleg i les dades comercials. No s'han afegit preus inventats.

## Publicar a GitHub Pages
1. Crea o inicia sessió a https://github.com/
2. Prem `New repository`. Posa-li un nom com `dismon-pastissos-web` i selecciona `Public`.
3. Afegeix els fitxers d'aquesta carpeta a l'arrel del repositori: `index.html`, `styles.css`, `script.js`, `config.js` i `README.md`. Pots fer-ho amb `Add file` → `Upload files`.
4. Prem `Commit changes`.
5. Entra a `Settings` → `Pages`.
6. A `Build and deployment`, selecciona `Deploy from a branch`, després `main` i `/ (root)`, i desa.
7. Espera uns minuts i torna a `Settings` → `Pages`; hi apareixerà l'enllaç publicat.

Si el nom del compte és `elmeunom` i el repositori és `dismon-pastissos-web`, l'adreça tindrà aquest format: `https://elmeunom.github.io/dismon-pastissos-web/`. El nom real depèn del teu compte.

## Què funciona i què no
- Selector d'idioma: català, castellà i anglès.
- El formulari prepara una consulta i obre WhatsApp perquè el client l'enviï manualment.
- Botó flotant de WhatsApp.
- No hi ha pagaments online, inventari ni gestió automàtica de comandes.
- No publiquis dades privades: un repositori públic és visible per tothom.
- Abans de publicar, afegeix i revisa les dades legals, de privacitat i cookies que siguin aplicables.

## Cost
GitHub Pages és gratuït per a repositoris públics amb GitHub Free. No cal comprar un domini: s'utilitza l'adreça gratuïta `github.io`. Les imatges i tipografies externes depenen dels seus proveïdors i requereixen internet.
