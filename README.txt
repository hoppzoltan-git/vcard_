Hopp Zoltán – NFC névjegy (Vercel)

A mappában:
- index.html: mobilbarát névjegyoldal
- contact.vcf: vCard 3.0 névjegyfájl

Telepítés:
1. Csomagold ki a ZIP-et.
2. Töltsd fel a két fájlt egy GitHub-repozitórium gyökerébe.
3. Vercelben válaszd az Add New -> Project lehetőséget, majd importáld a repót.
4. Framework Preset: Other. Build Command maradjon üres; a gyökérben lévő index.html lesz a kezdőoldal.
5. Deploy után nyisd meg a kapott HTTPS-címet iPhone-on és Androidon.
6. Sikeres teszt után NFC Tools -> Write -> Add a record -> URL/URI, és a Vercel HTTPS-címet írd a kártyára.

A kártyára a weboldal URL-je kerüljön, ne a VCF-fájl közvetlen címe.
A névjegy mentéséhez a weboldalon a „Kapcsolat mentése” gombra kell koppintani.
