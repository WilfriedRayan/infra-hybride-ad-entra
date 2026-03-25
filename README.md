# Infra Hybride AD / Entra

## Objectif
Ce projet simule une petite infrastructure hybride pour une PME de 100 a 200 utilisateurs.

Le but est de construire un environnement de labo realiste permettant de pratiquer :
- l'administration Windows Server
- Active Directory Domain Services
- DNS et DHCP
- les GPO
- un serveur de fichiers avec permissions NTFS et partages
- un serveur Linux de bastion / administration
- la synchronisation d'identite avec Microsoft Entra ID
- le MFA, les groupes, les roles
- les procedures d'onboarding et d'offboarding

## Perimetre technique
- 1 controleur de domaine Windows Server
- 1 serveur de fichiers Windows Server
- 1 serveur Linux
- 1 poste client Windows
- 1 tenant Microsoft Entra ID

## Architecture
![Architecture du labo](assets/diagramme-labo.png)

Voir la documentation detaillee :
- [Objectifs](docs/01-objectifs.md)
- [Architecture](docs/02-architecture.md)
- [Installation DC](docs/03-installation-dc.md)
- [Configuration AD](docs/04-configuration-ad.md)
- [Poste client et GPO](docs/05-poste-client-et-gpo.md)
- [Serveur fichiers](docs/06-serveur-fichiers.md)
- [Linux bastion](docs/07-linux-bastion.md)
- [Entra Sync](docs/08-entra-sync.md)
- [MFA et roles](docs/09-mfa-et-roles.md)
- [Onboarding / Offboarding](docs/10-onboarding-offboarding.md)
- [Tests et validation](docs/11-tests-validation.md)

## Machines prevues
- DC01 : AD DS, DNS, DHCP
- FS01 : serveur de fichiers
- LNX-ADM01 : bastion / outils reseau
- PC01 : poste client de test

## Competences demontrees
- administration Windows Server
- structuration Active Directory
- gestion reseau de base
- gestion d'identite hybride
- documentation technique
- tests et validation

## Auteur
Projet realise dans le cadre d'un apprentissage de l'administration systeme et de l'identite hybride.
