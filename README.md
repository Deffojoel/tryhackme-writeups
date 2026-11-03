# TryHackMe Write-ups

Dépôt personnel documentant mes rooms et CTF réalisés sur [TryHackMe](https://tryhackme.com), dans le cadre de ma formation en cybersécurité (Mastère Cybersécurité — Sup de Vinci, ANSSI SecNumedu).

Chaque write-up suit la même structure : **reconnaissance → exploitation → post-exploitation → flags**, avec captures d'écran à l'appui, et se termine systématiquement par deux sections volontairement mises en avant :

- **Ce qu'il faut retenir** — la compétence ou le concept clé démontré à chaque étape.
- **Recommandations défensives** — comment un défenseur (Blue Team) aurait pu prévenir, détecter ou limiter l'attaque documentée.

L'objectif n'est pas seulement de "capturer le flag", mais de comprendre *pourquoi* chaque vulnérabilité existe et comment s'en prémunir en environnement réel.

> ⚠️ Toutes les cibles documentées ici sont des machines volontairement vulnérables, fournies par TryHackMe dans un cadre pédagogique autorisé et isolé (VPN de lab, machines jetables). Aucune technique décrite dans ce dépôt ne doit être appliquée en dehors d'un environnement pour lequel on dispose d'une autorisation explicite.

## Rooms documentées

| Room | Catégorie | CVE / Technique | Statut | Write-up |
|---|---|---|---|---|
| [Blue](https://tryhackme.com/room/blue) | Exploitation Windows / SMB | MS17-010 (EternalBlue) | ✅ Terminé | [`rooms/blue-eternalblue/`](rooms/blue-eternalblue/README.md) |

*(De nouvelles rooms seront ajoutées au fur et à mesure.)*

## Structure du dépôt

```
tryhackme-writeups/
├── README.md                      ← ce fichier (catalogue)
└── rooms/
    └── <nom-room>/
        ├── README.md               ← write-up complet de la room
        └── assets/                 ← captures d'écran référencées dans le README
```

## À propos

Rédigé par **Alain Joël Deffo Neda** — étudiant en cybersécurité, ISC2 Certified in Cybersecurity (CC).
Portfolio : [deffojoel.github.io/portfolio](https://deffojoel.github.io/portfolio/)
