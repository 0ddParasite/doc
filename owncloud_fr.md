#Owncloud

**Comment d�placer son r�pertoire Owncloud sur un disque USB?**

**Pr�requis :** conna�tre les commandes d'administration Linux

Le r�pertoire data de Owncloud (contenant les fichiers) doit normalement �tre dans
```bash
/home/yunohost.app/owncloud/data
```

Il est possible de d�placer ce dossier vers un disque externe en USB (par exemple).

Il faut pour cela sp�cifier le nouveau chemin dans le fichier

```bash
/var/www/owncloud/config � la ligne datadirectory
```

Il faut s'assurer de bien mettre les droits � Owncloud sur ce r�pertoire

```bash
chown -R owncloud /le/chemin
```

Il faut aussi que le disque dur externe soit mont� automatiquement au d�marrage de Yunohost.