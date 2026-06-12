# Wiki Struktur & Crawling-Notizen

## Quelle
https://dsa.ulisses-regelwiki.de

## Inhalt
Nur DSA5 Regelwerk (kein Lore). Crunch-Elemente: Zauber, Liturgien,
Sonderfertigkeiten, Vor/Nachteile, Bestiarium, etc.

## Sitemap
https://dsa.ulisses-regelwiki.de/sitemap.xml
Vorhanden – alle Artikel-URLs direkt verfügbar.
Crawler-Strategie: Sitemap parsen statt Links folgen.

## URL-Struktur
Gemischt:
- Flach: /ArtikelName.html
- Verschachtelt: /kategorie/unterkategorie/artikel.html

Crawling-Regel: Alle URLs auf dsa.ulisses-regelwiki.de folgen,
besuchte URLs tracken um Duplikate zu vermeiden.

## Kategorienbaum
Variable Tiefe (2-4+ Ebenen), linke Navigationsleiste.

## Crawling-Regeln
- Nur URLs auf dsa.ulisses-regelwiki.de folgen
- Interne Artikellinks im Text folgen
- Externe Links ignorieren (e-shop etc.)
- Filter-/Listenansichten ignorieren, nur Artikel extrahieren

## Aventurica Wiki
https://de.wiki-aventurica.de/
- Lore, Geschichte, Geographie, NSCs etc.
- MediaWiki-Struktur, komplexer als Regelwiki
- Geplant für Phase 2, nach funktionierendem Regelwiki-Crawler