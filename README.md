# Fantasy Survivors — Public Releases

Ce dépôt contient uniquement les distributions publiques de Fantasy Survivors.
Le code source et la documentation de développement vivent dans un dépôt séparé.

## Stable

- Version courante : consulter `version.json`.
- Launcher Windows x64 :
  `downloads/0.1.1/win-x64/launcher/FantasySurvivors.Launcher.exe`
- Hashes : `SHA256SUMS.txt`.

Les exécutables sont self-contained pour Windows x64. Le launcher vérifie la
taille et le SHA-256 du package avant installation, conserve la version
précédente comme rollback et installe sous `%LOCALAPPDATA%\FantasySurvivors`.

Le launcher publié lit le manifest stable depuis
`raw.githubusercontent.com/capisoft-lib/FantasySurvivors-Releases/main/version.json`.
