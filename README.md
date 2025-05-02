# FCSC 2024 Horreur, malheur 2/5 - Accès initial

Vous venez d’être embauché en tant que Responsable de la Sécurité des Systèmes d’Information (RSSI) d’une entreprise stratégique.

En arrivant à votre bureau le premier jour, vous vous rendez compte que votre prédécesseur vous a laissé une clé USB avec une note dessus : ```VPN compromis (intégrité). Version 22.3R1 b1647```.

Sur la clé USB, vous trouvez deux fichiers : une archive chiffrée et les journaux de l’équipement. Vous focalisez maintenant votre attention sur les journaux. L’équipement étant compromis, vous devez retrouver la vulnérabilité utilisée par l’attaquant ainsi que l’adresse IP de ce dernier.

Le flag est au format : ```FCSC{CVE-XXXX-XXXXX:<adresse_IP>}```


Cette épreuve a été découpée en cinq parties :

- Horreur, malheur 1/5 - Archive chiffrée.
- **Horreur, malheur 2/5 - Accès initial**.
- Horreur, malheur 3/5 - Simple persistance.
- Horreur, malheur 4/5 - Pas si simple persistance.
- Horreur, malheur 5/5 - Un peu de CTI.

Auteur : \E

Origine : [Horreur, malheur 2/5 - Accès initial](https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-2/)


Fichiers :
- [horreur-malheur.tar.xz](horreur-malheur.tar.xz)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-horreur-malheur-2.git

> cd fcsc2024-forensics-horreur-malheur-2


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-2/