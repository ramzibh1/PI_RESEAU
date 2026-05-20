# TechSolutions SARL - Département Supervision/IT (RZ-2)

## 📋 Description du Projet

Projet de déploiement d'une infrastructure réseau multiservice pour **TechSolutions SARL**.  
Ce dépôt concerne le **département Supervision/IT** (RZ-2) avec mise en place d'une solution complète de monitoring.

### 🎯 Objectifs atteints
- Configuration complète du routeur **RZ-2** (OSPF, DHCP, NAT/PAT)
- Adresse publique officielle : **203.0.113.5/30**
- Bloc LAN : **172.24.64.0/21** (VLSM conforme CDC)
- Supervision centralisée avec **Prometheus + Grafana**
- Deux VMs distinctes : `vm-serveur-rs` et `vm-client`
- Monitoring de tous les départements (Web, Gestion, Collaboration)

---

## 📁 Structure du Projet

- **Cahier_des_charges/** → Document officiel du projet
- **GNS3/** → Topologie et configurations GNS3
- **Configurations_Réseau/** → Configurations Cisco IOS
- **Scripts_Shell/** → Scripts d'automatisation (obligatoire)
- **Documentation/** → Rapport technique + captures
- **VMs/** → Configurations des machines virtuelles
- **Screenshots/** → Preuves de fonctionnement

---

## 🛠️ Technologies Utilisées

- **Routage** : OSPF Area 0
- **Adressage** : VLSM + NAT/PAT
- **Supervision** : Prometheus + Grafana + Node Exporter
- **Automatisation** : Scripts Shell
- **Outils** : GNS3, VMware Workstation, Cisco IOS

---

## 🚀 Accès aux Services

| Service              | URL / IP                     | Port   | Identifiants          |
|----------------------|------------------------------|--------|-----------------------|
| Grafana              | http://172.24.x.x:3000     | 3000   | admin / (changé)      |
| Prometheus           | http://172.24.x.x:9090     | 9090   | -                     |
| Node Exporter (Serveur) | http://172.24.x.x:9100  | 9100   | -                     |
| Node Exporter (Client)  | http://172.24.x.x:9100  | 9100   | -                     |

---

## 📸 Captures Importantes

- Topologie GNS3 complète
- Dashboard Grafana (tous les départements)
- Prometheus Targets (5 jobs UP)
- Configuration OSPF + Voisinages
- DHCP Binding

---

## 👨‍💻 Auteur

- **Nom** : Ramzi
- **Département** : Supervision / IT (RZ-2)
- **Projet** : TechSolutions SARL - Infrastructure Réseau Multiservice

---

**Projet réalisé dans le cadre du module "Administration des Services Réseaux"**

---

⭐ N'hésite pas à donner une étoile si ce projet t'a aidé !
