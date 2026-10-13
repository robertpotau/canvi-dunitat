# Canvi d'Unitat
Joc d'un sol fitxer (`index.html`, JS vanilla, sense dependències; només la font Nunito de Google Fonts).
- Decimals exactes amb cadenes (`shift`, `norm`, `fmt`); mai floats per a les respostes.
- Dades: `MAGS` (unitats i exponent per pas: 1/2/3), `PROBS` (plantilles de problemes), `MODES`.
- Generadors `genConvert/genFactor/genFill/genProblem/genChain`; motor a `startGame/nextQ/evaluate/finish`.
- Verificació: obrir `index.html?selftest` (serveix amb `python -m http.server`; els file:// no executen en el panell del navegador).
- Perfil a localStorage clau `canvi-dunitat-v1`. No posar noms d'alumnes al repositori.
- Publicat com a "En Construcció" a la secció de Mates de robertpotau.github.io.
