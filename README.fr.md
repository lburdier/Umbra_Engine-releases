[English](README.md) · **Français**

# Umbra Editor - téléchargements

Moteur et éditeur de jeux d'horreur rétro, pour Windows (Direct3D 11).

Ce dépôt ne contient que les **versions publiées** d'Umbra Editor.

## Installer

1. Ouvre la [dernière release](../../releases/latest).
2. Télécharge **`UmbraEngine-Setup.exe`** et lance-le.
3. C'est tout : l'installeur télécharge la dernière version, vérifie son
   empreinte SHA-256 et l'installe dans ton profil
   (`%LOCALAPPDATA%\Programs\Umbra Engine`), sans droits d'administrateur.

L'installeur n'est pas signé : Windows SmartScreen peut afficher
« Windows a protégé votre ordinateur ». Clique sur **Informations
complémentaires**, puis **Exécuter quand même**.

### Sans installeur

Télécharge `UmbraEngine-<version>-win64.zip`, extrais-le où tu veux et lance
`umbra_editor.exe`. Le dossier se met à jour de la même façon.

## Mises à jour

L'éditeur vérifie au lancement s'il existe une version plus récente. Elle
s'annonce par une notification ; un clic la télécharge, et elle s'installe au
redémarrage. Ton contenu (`content/`) n'est jamais remplacé.

## Désinstaller

Paramètres Windows > Applications > Applications installées > Umbra Engine >
Désinstaller. Ton contenu et tes réglages restent sur le disque, sauf si tu
coches la case pour tout supprimer.

## Vérifier un téléchargement

Chaque paquet a son fichier `.sha256` :

```powershell
Get-FileHash UmbraEngine-1.0.0-win64.zip -Algorithm SHA256
```

---

Umbra Editor est un logiciel propriétaire ; le code source n'est pas public.
