# Librairie Hadoop pour Windows

Afin de pouvoir utiliser correctement Spark avec le système de fichier Windows il est nécessaire de disposer du binaire winutils.exe.
Ce binaire permet d'ecrire des données depuis Spark le système de fichier Windows

Spark attend ```winutils.exe``` dans l'installation Hadoop "<Répertoire d'installation Hadoop>/bin/winutils.exe" (notez le dossier "bin")

### Création de HADOOP_HOME

- Créer un un répertoire pour les binaire hadoop: e.g: ```C:\Program Files\hadoop\bin\```
- Télécharger le fichier ```winutils.exe```
- Placer le fichier ```winutils.exe``` dans le répertoire ```..\hadoop\bin\```


#### Definir la variable d'environnement ```HADOOP_HOME```

- Sous Windows 10 et Windows 8 accédez à ``` Panneau de configuration> Système> Paramètres système avancés.```
- Windows 7, cliquez avec le bouton droit sur Poste de travail et sélectionnez ``` Propriétés> Avancé.```
- Cliquez sur le bouton Variables d'environnement.
- Sous Variables système, cliquez sur Nouveau.
- Dans le champ Nom de variable, entrez: ```HADOOP_HOME ```
- Dans le champ Valeur , entrez votre chemin du répertoire ```hadoop``` . e.g: ```C:\Program Files\hadoop```
- Cliquez sur OK et appliquez les modifications 


