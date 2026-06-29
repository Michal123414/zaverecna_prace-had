# Snake 🐍

Klasická hra Had vytvořená v Pythonu pomocí knihovny pygame.

## Funkce

- Plynulé ovládání (WASD + šipky)
- Zvukové efekty (snědení jablka, game over, pohyb)
- Postupné zrychlování podle skóre
- Restart po umření
- Možnost pauzy chybí záměrně – hra je tak o trochu těžší
- Top skóre, které si pamatuje váš nejlepší výsledek

## Požadavky

- Python 3.13
- pygame (externí knihovna – nutno doinstalovat)

Hra dále využívá vestavěné moduly `random`, `sys` a `hashlib`, které jsou součástí Pythonu a není potřeba je instalovat.

## Instalace

```
python3.13 -m pip install pygame
```

## Spuštění

Ve složce projektu spusť:

```
python3.13 had.py
```

> Důležité: hru spouštěj ze složky projektu, aby se správně načetly zvuky ze složky `sounds/`.

## Ovládání

| Klávesa      | Akce              |
|--------------|-------------------|
| Šipky / WASD | Pohyb hada        |
| R            | Restart po prohře |
| ESC          | MENU              |