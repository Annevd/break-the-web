> _Fork_ deze deeltaak en ga aan de slag. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Break the Web

Doe het web het een beetje goed?

## Hema.nl
 
Op **15 april 2024** heb ik de website van [HEMA](https://hema.nl) getest. Ik heb HEMA gekozen omdat ik zelf bij een HEMA werk en ik benieuwd was hoe goed zo'n grote website eigenlijk is. Er zijn namelijk genoeg interacties en elementen om te onderzoeken.

![image](https://github.com/Annevd/break-the-web/assets/144004647/3dc88c83-8684-418b-9c61-b8cfd61bb8aa)

**Resultaten:**

<img height= 470 src="https://github.com/Annevd/break-the-web/assets/144004647/70e4a0eb-aad7-458a-9681-5badea24244a">
<img height= 470 src="https://github.com/Annevd/break-the-web/assets/144004647/4307950b-56a7-425e-bbd6-4b4a88a603b8">

Om deze website te testen heb ik een lighthouse test gedaan, Pagespeed Insights gebruikt en de features Javascript en Ad/contentblockers onderzocht.
Hema scoorde goed op de metrics **First Contentful Paint (FCP)**, **Largest Contentful Paint (LCP)** en **Cumulative Layout Shift (CLS)**. Bij **Total Blocking Time (TBT)** en **Speed Index** is er nog genoeg ruimte voor verbetering.

Om de **Speed Index** te verbeteren is het belangrijk dat je je pagina's zo licht mogelijk maakt door afbeeldingen te optimaliseren (compressen) en onnodige scripts/code te verwijderen. Hoe sneller de pagina opbouwt, hoe beter!

Om de **Total Blocking Time** te verbeteren is het belangrijk om je code te optimaliseren en zo weinig mogelijk zware functies te gebruiken.

Ook heb ik de website getest met én zonder **adblocker** en heb ondervonden dat de website trager is mét een adblocker.
Daarnaast heb ik getest of de website werkte **zonder Javascript**. In dit geval had de website nog een aantal problemen.

Mijn uitgebreide testbevindingen zijn te lezen in mijn [wiki](https://github.com/Annevd/break-the-web/wiki).


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
