# Craft

Logiciel de patronage 2D pour la maroquinerie, pour Windows 10 et 11.

## Installer Craft

1. Téléchargez **[Craft_Installation.zip](https://github.com/DurandCuir/Craft/raw/main/Craft_Installation.zip)**.
2. Faites un clic droit sur le fichier téléchargé, puis **Extraire tout…**, et ouvrez le dossier extrait.
3. Double-cliquez sur **Installer Craft**.
   Si Windows affiche « Windows a protégé votre ordinateur » : **Informations complémentaires**, puis **Exécuter quand même**.
4. Cliquez sur **Installer**, puis sur **Ouvrir Craft**.
5. Dans Craft : menu **Aide › Activer une licence…**, collez la clé de licence reçue, puis **Activer**.

Rien d'autre à installer, pas besoin d'être administrateur.

## Mises à jour

Craft les cherche tout seul sur Internet (une fois par jour au plus) et propose **Redémarrer** quand une nouvelle
version est prête. Craft ne fait que télécharger : rien n'est envoyé sur vous.

## Licence

Craft demande une clé de licence à votre nom : demandez-la à la personne qui vous a partagé Craft.
Sans clé, l'essai complet dure 30 jours ; ensuite, seul l'export (PDF, DXF, SVG, DWG) demande la licence.
Vos patrons restent toujours ouverts et enregistrables.

## Désinstaller

Paramètres de Windows › Applications › Craft › Désinstaller. Vos patrons, vos réglages et votre licence sont gardés.

## Logiciels libres livrés avec Craft

- Python 3.12 (licence de la Python Software Foundation, avec celles de Tcl/Tk, OpenSSL et des autres bibliothèques
  de Python : fichier `Python\LICENSE.txt`).
- GNU LibreDWG 0.13.3 (GNU GPL v3 ou ultérieure), pour ouvrir et écrire les DWG : son code source et le correctif de
  Craft sont dans le dossier [sources](sources) (`LibreDWG-0.13.3-sources.tar.gz`, `LibreDWG-0.13.3-craft.patch`).
- Les certificats racine de Mozilla (licence MPL 2.0), pour la connexion sécurisée des mises à jour.
