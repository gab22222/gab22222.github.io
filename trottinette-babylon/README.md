# Trottinette Babylon

La même balade que [Trottinette](https://gab22222.github.io/trottinette/), avec la même physique, les mêmes commandes, radars, nuages et chutes, mais un rendu refait avec le moteur Babylon.js (9.30) au lieu de three.js.

Pour jouer : https://gab22222.github.io/trottinette-babylon/

- **Rendu** : matériaux PBR, éclairage et reflets calculés depuis le ciel, ombres douces, tone mapping ACES, bloom sur les lumières (LED, feux, étincelles, flash des radars), aberration chromatique qui monte avec la vitesse.
- **Graphismes** : chaque preset règle la définition et les effets. Low : sans bloom, ombres plus légères. Medium (par défaut) : bloom et FXAA. High et Ultra : anticrénelage MSAA x4 et ombres à contact durci (PCSS), et en Ultra des ombres plus fines.
- Plus lourde à charger que la version three.js (environ 1,5 Mo pour le moteur).
