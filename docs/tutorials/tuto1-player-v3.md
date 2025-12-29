# Tuto 1 – Player et déplacements
@tutorial

## Étape 1 : Créer le personnage
@step

Crée un personnage joueur.

- Va dans **Sprites**
- Ajoute un bloc **créer un sprite**
- Choisis **Player** comme type

```blocks
let player = sprites.create(img`
    . . . . .
    . 2 2 2 .
    . 2 . 2 .
    . 2 2 2 .
    . . . . .
`, SpriteKind.Player)
```

