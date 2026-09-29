# Martellata Campo

App per la **martellata e la matricinatura dei cedui** (Basilicata, Campania, Calabria): piedilista pianta per pianta numerato, collegato a QGIS / QField / QFieldCloud.

- **Web:** https://gennaroventura66-creator.github.io/martellata-campo/
- **Android (APK):** https://github.com/gennaroventura66-creator/martellata-campo/releases/latest/download/Martellata-Campo.apk

## Cosa fa
- Lotti di taglio con aree (confine, sezioni, aree escluse) disegnate in QGIS o in app.
- Registrazione rapida delle piante: numero progressivo per operatore, specie, diametro, altezza, destinazione (taglio / matricina / confine), età della matricina, stato; tastierino e dettatura ("CA24 CE31 h18").
- Cubatura albero per albero: equazioni INFC 2005 per 71 specie di latifoglie e conifere, curve ipsometriche dai campioni, **tavole del PAF** (una entrata, doppia entrata, coefficienti).
- Verifiche normative (Calabria R.R. 4/2024: turni, matricine/ha, matricine ≥ 2T, tagliata massima, periodo). Per Basilicata e Campania i valori si inseriscono in Altro → Norme regionali.
- Stampe: piedilista di martellata e di matricinatura (PDF), verbale (PDF / Word), relazione di stima (Word), fascicolo completo con carta, Excel, CSV.
- Scambio con QGIS tramite `martellata.gpkg` + `Martellata.qgz`; sincronizzazione QFieldCloud a più operatori (unione a tre vie) nell'app Android.

## Partire da QGIS
Scarica `Martellata_QGIS.zip` (in app: Altro → Kit QGIS vuoto), apri `Martellata.qgs`, disegna aree e compila il lotto, poi importa il GeoPackage nell'app o caricalo su QFieldCloud.

## Firma dell'APK
Per installare gli aggiornamenti sopra la versione precedente serve il secret `ANDROID_KEYSTORE` (Settings → Secrets and variables → Actions), da inserire a cura del proprietario del repository.
