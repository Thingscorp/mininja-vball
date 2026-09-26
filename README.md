# Mininja-vball

Side-quest slime volleyball with the unnamed [Mininja](https://github.com/Thingscorp/mininja) mark as the blob.

Local two-player. Not part of the Mininja console/bot kit — arcade next door.

## Play

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8765 --directory .
# then http://localhost:8765
```

| Side | Move | Jump |
|------|------|------|
| Left (indigo) | A / D | W |
| Right (cream) | ← / → | ↑ |

First to drain the other of **5 lives** wins. `R` restarts after match point. `Esc` pauses.

## Cred

Inspired by classic [oneslime.net](http://oneslime.net/) slime volleyball, [parsiad/slime-vball](https://github.com/parsiad/slime-vball) (C/SDL), and [hardmaru/slimevolleygym](https://github.com/hardmaru/slimevolleygym) / Neural Slime Volleyball. This tree is a clean MIT rewrite — no GPL sources vendored.

Mark language from Thingscorp Mininja (unnamed mascot; no Casque).

## Scope

- v0: canvas court, net, two local pals, ball, lives
- Not: Gym/RL, kit SoT, console habitat locomotion, provider themes
