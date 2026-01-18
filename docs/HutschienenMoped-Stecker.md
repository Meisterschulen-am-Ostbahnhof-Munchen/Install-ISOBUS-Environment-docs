# HutschienenMoped Stecker

```{index} single: HutschienenMoped Stecker
```

Diese Fotostrecke dokumentiert die korrekte Verkabelung und die verwendeten Steckertypen für das „HutschienenMoped“-Modul.

## 🎧 Podcast

* [Der IBBC: Wie Stecker, Kabel und ISO 11783 Hightech-Landmaschinen verbinden](https://podcasters.spotify.com/pod/show/ms-muc-lama/episodes/Der-IBBC-Wie-Stecker--Kabel-und-ISO-11783-Hightech-Landmaschinen-verbinden-e36t2lk)
* [Hutschienenmoped XL: ISOBUS ECU Entwicklung](https://podcasters.spotify.com/pod/show/ms-muc-lama/episodes/Hutschienenmoped-XL-ISOBUS-ECU-Entwicklung-e368hdg)

## 📺 Video

* [2025 11 15 12 35 11 Montage Hutschienenmoped logiBUS® -- Teil 3 -- Gehäuse](https://www.youtube.com/watch?v=MPm4vLmD5RE)
* [2025 11 15 12 52 26 Montage Hutschienenmoped logiBUS® -- Teil 4 -- Aufbauten](https://www.youtube.com/watch?v=WeowCxZW70Y)
* [2025-11-13 17-50-42 Montage Hutschienenmoped logiBUS® -- Teil 1 -- Einführung und Löten](https://www.youtube.com/watch?v=HWBMBVLMPiw)
* [2025-11-15 12-19-33 Montage Hutschienenmoped logiBUS® -- Teil 2 -- Einführung und Löten](https://www.youtube.com/watch?v=nohE36SZY9M)
* [2025-12-14 20-03-27 Aufspielen Training 1 Übung 1 auf das Hutschienenmoped.](https://www.youtube.com/watch?v=6iog7-DZvW0)

## 1. Grundlegende Verdrahtung und Anschlüsse

Die Basisverdrahtung des Moduls auf der Hutschiene erfolgt über rote und schwarze Leitungen (Spannungsversorgung und Masse), die über Flachsteckhülsen mit den Stiftleisten der Platine verbunden sind.

* **Steckertyp:** Standardmäßig kommen hier **6,3 mm Flachsteckhülsen** zum Einsatz.

```{image} https://user-images.githubusercontent.com/69573151/131330812-b4942f7e-a731-4321-9e51-265eb43abbad.jpg
```

6.3mm Flachsteckhülsen

```{image} https://user-images.githubusercontent.com/69573151/131330809-b7043bb2-fcd6-4867-a0a5-d52e81da76a4.jpg
```

```{image} https://user-images.githubusercontent.com/69573151/131330810-7f8057b1-0ae5-4497-8c75-95dd7f46063d.jpg
```

## 2. Isolierung und Berührungsschutz

Um Kurzschlüsse zwischen den eng beieinanderliegenden Kontakten zu vermeiden und die Berührungssicherheit zu gewährleisten, werden die Flachsteckhülsen isoliert. Rote und schwarze Isoliertüllen (oder Schrumpfschläuche) umschließen die Crimpstellen und den hinteren Teil der Steckverbinder vollständig.

```{image} https://user-images.githubusercontent.com/69573151/131330811-2f7aac87-ee6a-43b9-9b88-493c8a4dabf7.jpg
```

## 3. Detailansicht: Spezielle Signalanschlüsse

Für spezifische Anschlüsse oder bei engeren Platzverhältnissen werden abweichende Größen verwendet. Das Bild zeigt den Einsatz von **zwei 2,8 mm Flachsteckhülsen**, die nebeneinander auf einem Anschlussblock sitzen. Dies ist wichtig für Kontakte, die mechanisch nicht für die breiteren 6,3 mm Hülsen ausgelegt sind.

```{image} https://user-images.githubusercontent.com/69573151/131330813-dfbfb0aa-dbbf-4bfe-945a-b828850712d3.jpg
```
2x 2.8mm Flachsteckhülsen

## 4. Steckverbindungs-Gehäuse und Gesamtansicht

Die fertig isolierten Leitungen werden sauber geführt. Für eine modularere Verbindung kommt zudem ein graues Steckergehäuse der Marke AMP (TE Connectivity) mit der Teilenummer **3-328343-8** zum Einsatz, um mehrere Kontakte zu bündeln.

```{image} https://user-images.githubusercontent.com/69573151/151920214-33806be9-d9f2-4f7b-bdd2-fc75bbbe0617.jpg
```

```{image} https://user-images.githubusercontent.com/69573151/151920219-a69512cb-bf9c-440f-978b-fcc0e3738edd.jpg
```

```{image} https://user-images.githubusercontent.com/69573151/151920231-29b82169-1637-42f6-aa9f-4a7a84869eb5.jpg
```

## 5. Betriebszustand

Das fertig verkabelte Modul im aktiven Betrieb: Die grünen LEDs leuchten im Inneren des Gehäuses, und die Peripherie ist angeschlossen.

```{image} https://user-images.githubusercontent.com/69573151/151920400-3f64befd-fb6f-40c0-babf-7adbad799925.png
```