Fräse iModela Einweisung
========================

:warning: __Entwurf:__ Einige Abschnitte fehlen noch (siehe TODOs im Dokument). :warning:

Einweisung des [FAU FabLab](https://fablab.fau.de) in die Mini-CNC-Fräse Roland iModela.

Inhalt
------

- Regeln und Hinweise, Datenaufbereitung (2,5D und 3D)
- Maschine vorbereiten: Ein-/Ausschalten, Aufklappen, manuelles Verfahren
- Material einlegen, Ursprung einstellen, Hinweise für Betreuer

Download
--------

Die neueste Version aus [GitHub](https://github.com/fau-fablab/fraese-imodela-einweisung) ist als PDF abrufbar:

- [Einweisung](https://brain.fablab.fau.de/build/fraese-imodela-einweisung/Einweisung_Fraese-iModela.pdf)

Außerdem baut eine GitHub Action die PDFs bei jedem Push. Auf dem Hauptbranch entsteht dabei ein
[Release](https://github.com/fau-fablab/fraese-imodela-einweisung/releases) mit Datums-Version (`vJJJJ.MM.TT`) und den PDFs.

Auschecken und bauen
--------------------

```bash
git clone --recursive git@github.com:fau-fablab/fraese-imodela-einweisung.git
cd fraese-imodela-einweisung
make
```

Die PDFs landen in `output/`. Layout, Kopf- und Fußzeile und das Logo des FAU FabLab (mit
FAU-Schriftzug) kommen aus dem Untermodul [fablab-document](https://github.com/fau-fablab/fablab-document),
das Logo wiederum aus dessen Untermodul [logo](https://github.com/fau-fablab/logo). Bei einem bestehenden
Klon die Untermodule mit `git submodule update --init --recursive` laden.

Technische Details zum Buildserver: [fau-fablab/buildserver](https://github.com/fau-fablab/buildserver)

[![Build Status](https://brain.fablab.fau.de/build/fraese-imodela-einweisung/status.svg)](https://brain.fablab.fau.de/build/fraese-imodela-einweisung/)
[![TODOs](https://brain.fablab.fau.de/build/fraese-imodela-einweisung/status-todos.svg)](https://brain.fablab.fau.de/build/fraese-imodela-einweisung/)
[![PDF bauen](https://github.com/fau-fablab/fraese-imodela-einweisung/actions/workflows/pdf.yml/badge.svg)](https://github.com/fau-fablab/fraese-imodela-einweisung/actions/workflows/pdf.yml)

Lizenz
------

[![Lizenz: CC BY-SA 3.0](https://licensebuttons.net/l/by-sa/3.0/de/88x31.png)</br>CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

Ausnahme: Viele Abbildungen stammen von Roland; für das Gesamtdokument ist die Lizenz daher noch ungeklärt.
