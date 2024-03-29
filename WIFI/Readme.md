# WIFI EXFILL

Ce script récupère les informations de connexion WIFI sur l'ordinateur local, les renvoie dans un fichier texte. Ce fichier texte est ensuite encodé en BASE64 puis envoyé sur un serveur distant via le protocole FTP.

Les identifiants du serveur distant sont créés localement via les variables d'environnement. Ensuite, la deuxième section du code est téléchargée et exécutée directement depuis la mémoire.

---

J'ai fait ce script purement dans un contexte d'apprentisage. 
