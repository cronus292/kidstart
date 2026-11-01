# Kinderstart — GitHub Pages

Vier onafhankelijke startpagina's: `kind1.html`, `kind2.html`, `kind3.html`, `kind4.html`.

## Publiceren (GitHub Free)

1. Maak via github.com/new een **public** repository `kinderstart`.
2. Upload **alle bestanden uit deze map** (niet de ZIP zelf) naar de hoofdmap van de repository en commit.
3. Ga naar **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Kies `main`, `/(root)` en **Save**.
5. Open `https://GEBRUIKERSNAAM.github.io/kinderstart/` (vervang GEBRUIKERSNAAM).
6. Open op de iPad in **Safari** `.../kind1.html` en tik **Delen → Zet op beginscherm**. Herhaal voor de andere kinderen.

## Links en persoonlijke instellingen

- Open de pagina, tik **Instellingen**, pas de naam aan en voeg links toe. Parameters (`?nolink=true`, enz.) blijven behouden.
- Links en naam worden via `localStorage` in die browser/webapp op **dat apparaat** bewaard, niet in GitHub en niet automatisch gesynchroniseerd.
- Gebruik **Exporteer JSON** en **Importeer JSON** om gegevens over te zetten naar een andere browser of iPad; dit is ook een eenvoudige back-up.
- Let op: de Safari-webapp kan een eigen opslagruimte hebben. Stel de pagina daarom in via het pictogram **nadat** je deze aan het beginscherm hebt toegevoegd.
- Het instellingenvenster is **niet beveiligd**: dit is geen ouderlijk-toezichtsysteem.
- Omdat GitHub Pages openbaar is, mogen er geen persoonlijke gegevens of geheime tokens in bronbestanden worden opgenomen.

## Fullscreen en Digipuzzle

De manifesten gebruiken `display: standalone` (iPadOS 17). Deze instelling verbergt de reguliere Safari-interface **voor de eigen Kinderstart-pagina**. Links naar een externe domeinnaam, zoals Digipuzzle, kunnen in Safari buiten de webapp openen. Ook kan Digipuzzle het insluiten in een iframe blokkeren. De instelling `?nolink=true` is alvast in de voorbeeldlink opgenomen, maar is **geen iPadOS-fullscreenparameter**.

## Toekomstige uitbreiding

Later is een centraal beheerde `config.json` mogelijk, zodat instellingen automatisch op alle apparaten gelijk zijn. Daarvoor is een wijziging in de applicatie nodig. Voor echt ouderlijk toezicht zijn iPadOS-beperkingen, DNS-controle en eventueel routerregels nodig.
