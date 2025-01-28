# 🏥🔒 SAE 502 : Sécurisation du Système Informatique d'un Hôpital

## 📜 Description de l'objectif

Ce projet vise à protéger les systèmes informatiques d'un hôpital contre les cyberattaques qui peuvent avoir des conséquences désastreuses :  
- **Blocage des systèmes informatiques**  
- **Perte de données médicales critiques**  
- **Interruption des soins urgents et des opérations médicales**  

Les attaques récentes sur des hôpitaux français montrent l'importance d'une protection renforcée. Les données médicales, très convoitées sur le marché noir, doivent être sécurisées.  

### Exemples d'incidents récents :  
- **30/06/2023** : Déni de service sur le site des Hôpitaux de Paris  
- **21/06/2023** : Cyberattaque à l'Hôpital de Rennes, utilisation de fax pour les communications  
- **03/2023** : Hôpital de Brest, mise en mode dégradé après une cyberattaque  
- **09/2022** : Hôpital Corbeil-Essonnes, vol de données et rançon de 10 millions de dollars  
- **2021** : Hôpital de Villefranche-sur-Saône, arrêt de 3000 ordinateurs  
- **2021** : Hôpital de Dax, perte des données médicales, coût de 2,4 millions d’euros  

---

## 🎯 Objectifs du Projet

### Sécurisation du Réseau :
1. Mise en place d’une **architecture réseau cloisonnée** :  
   - **Direction**  
   - **Administration**  
   - **Données médicales**  
2. **Authentification sécurisée** avec le standard 802.1X (filaire et sans fil).  
3. Création d’un **VPN sécurisé** entre deux hôpitaux pour l’échange de données médicales.  

### Gestion des Ressources :
4. **Bases de données** des personnels et des patients sur des serveurs dédiés.  
5. **Serveur de direction** pour gérer les données administratives de haut niveau.  
6. Mise en place de procédures pour :  
   - Sauvegarde et restauration des données.  
   - Réinstallation automatisée des serveurs.  
   - Basculement entre le serveur principal et le serveur de secours.  

---

## 🛠️ Tâches Réalisées

1. **Construction d’une architecture réseau sécurisée** et cloisonnée.  
2. **Configuration du standard 802.1X** pour authentifier les utilisateurs selon leurs rôles.  
3. **Mise en place de restrictions d’accès** :  
   - Accès à la salle d’opération uniquement pour le personnel médical pendant les opérations.  
   - Accès autorisé pour l’entretien uniquement en dehors des heures médicales.  
4. **Création et gestion des serveurs** :  
   - Direction, administration, médical et VPN.  
   - Bases de données sécurisées pour les personnels et les patients.  
5. **Procédures de continuité des services** :  
   - Sauvegarde et restauration des serveurs.  
   - Automatisation de la réinstallation des serveurs.  
   - Basculement dynamique entre le serveur principal et le serveur de secours.  
6. **VPN sécurisé** : Communication entre deux hôpitaux sans accès à Internet.  

---

## ⚙️ Matériel Utilisé

- **2 Switches Cisco Catalyst C34/5XX**  
- **1 Borne WiFi Linksys WRT54G**  
- **1 Routeur Cisco 1841/1900** pour la gestion des accès et des droits.  
- **4 Serveurs** :  
  - Direction  
  - Administration  
  - Médical  
  - VPN  
- **Postes clients et un ordinateur portable** compatibles avec 802.1X.  
- **Smartphone Android** avec prise en charge de 802.1X.  

---

## 🚀 Méthodologie

1. **Planification de l’architecture** sur **GNS3** :  
   - Simulation des configurations réseau avant déploiement réel.  
2. Utilisation de **GitHub** pour :  
   - Sauvegarder les configurations réseau.  
   - Versionner les scripts et la base de données.  

---

## 📚 Documentation

- Chaque tâche est accompagnée d’une documentation détaillée permettant au personnel informatique de :  
  - Comprendre les configurations.  
  - Répliquer les procédures.  
  - Résoudre rapidement les problèmes.  

---

## 🤝 Collaboration et Suivi

- **Versionnage sur GitHub** : Collaboration efficace pour les configurations réseau et les scripts.  
- **Documentation centralisée** pour garantir une continuité de service en cas de changement d'équipe.  

---

## 🔐 Résultats Attendus

- **Protection renforcée** contre les cyberattaques.  
- **Continuité des services** médicaux et administratifs.  
- **Échange sécurisé** de données médicales entre hôpitaux.  

---

## 🧑‍💻 Auteur

**Altay Cevik**  
📩 Contact : altaycevik@gmail.com  
