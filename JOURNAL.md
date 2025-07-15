# Journal de progression

2025-07-15  
Avancée majeure sur le projet Jenkins CI/CD Pipeline. Après plusieurs essais, j’ai réussi à déployer Jenkins sur une VM Ubuntu via Vagrant avec Java 17. Mise en place d’un Jenkinsfile pour une pipeline basique intégrant build, lint et tests.  
Un push Git s’est malencontreusement retrouvé dans le dépôt Zabbix Monitoring, ce qui a compliqué la gestion des versions. Après plusieurs manipulations Git (stash, rebase, reset), j’ai dû supprimer le repo Zabbix sur GitHub pour repartir sur une base propre. Cette expérience m’a permis de mieux comprendre la gestion avancée des branches et des conflits.  
Ajout d’un dossier `setup/` et d’un fichier `notes.md` pour structurer les scripts et documenter mes erreurs et solutions. Le projet Jenkins prend forme, prêt à être enrichi.

2025-07-10  
Travail sur le projet Secure_Webserver_Ubuntu : déploiement d’un serveur Nginx sécurisé avec HTTPS auto-signé dans une VM Ubuntu. La configuration du certificat et du firewall UFW a nécessité plusieurs tests et corrections. Problèmes de redirection HTTP vers HTTPS et ouverture des ports. Finalement, tout fonctionne correctement.  
Documentation complète avec README et organisation claire du projet. Ce projet a renforcé mes compétences en administration système et sécurité réseau.

2025-07-05  
Projet Zabbix Monitoring complexe à configurer. Installation et paramétrage de l’agent de supervision dans la VM Ubuntu ont demandé de nombreux ajustements, notamment sur les permissions et le provisioning.  
La confusion entre les dépôts Jenkins et Zabbix a généré des erreurs de push. J’ai approfondi ma maîtrise de Git pour résoudre ces conflits, utilisant stash, rebase, reset. J’ai finalement supprimé le repo Zabbix distant pour repartir propre. Je prévois de recréer ce repo avec une meilleure organisation.

2025-06-23  
Finalisation du provisioning Vagrant avec un script shell installant Samba, Apache2, htop, curl et vim. Plusieurs itérations pour corriger des erreurs liées aux permissions et dépendances.  
Tests concluants sur la VM pour le partage Samba et le serveur web local. Push initial vers GitHub avec .gitignore optimisé.

2025-06-22  
Approfondissement des configurations Samba et Apache2. Résolution de problèmes liés aux droits d’accès. Validation des partages et du serveur web.

2025-06-21  
Écriture et test du script de provisioning. Automatisation de l’installation d’outils essentiels. Ajustements nécessaires pour garantir le bon déroulement des commandes.

2025-06-20  
Installation et configuration des VM Ubuntu et Windows 10 Pro via VirtualBox. Introduction à Wireshark et Advanced IP Scanner pour analyser le trafic réseau entre VM. Premiers diagnostics réseau réussis.

2025-06-19  
Apprentissage des commandes Linux de base et compréhension approfondie du modèle OSI.

2025-06-18  
Configuration réseau entre VMs Ubuntu et Windows. Tests de connectivité validés (ping, traceroute). Ajustements des interfaces réseau.

2025-06-10  
Progrès sur OverTheWire Bandit jusqu’au level 12. Renforcement des compétences en ligne de commande et sécurité.

2025-06-09  
Approfondissement des commandes shell et gestion de fichiers sous Linux.

2025-06-08  
Installation des outils essentiels : Git, VirtualBox, Vagrant. Premiers pas dans la virtualisation et gestion de configuration.

2025-05-22  
Début de la formation Technicien Systèmes et Réseaux. Mise en place des outils et premiers contacts avec l’administration système.
