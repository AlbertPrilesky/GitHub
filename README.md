# Čtení textového souboru v Pythonu

Jednoduchý skript pro načtení a vypsání obsahu textového dokumentu.

## Popis kódu
- Používá modul `os` a funkci `os.sep.join()` pro správné sestavení cesty k souboru nezávisle na operačním systému (Windows / Linux / macOS).
- Soubor se otevírá pomocí konstrukce `with open()`, která zajistí jeho automatické uzavření po přečtení.
- Kódování je nastaveno na `utf-8` kvůli podpoře české diakritiky.

## Struktura složek
Aby skript fungoval, musí existovat podsložka `soubory` s příslušným textovým souborem:

```text
├── skript.py
└── soubory/
    └── textovydokument.txt
