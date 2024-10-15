# Sniffer Réseau en Python

## Description
Ce projet consiste en un sniffer réseau développé en Python. Le script utilise la bibliothèque Scapy pour capturer et analyser le trafic réseau en temps réel. Il permet d'extraire des informations détaillées sur les paquets, y compris les adresses IP source et destination, les ports utilisés, et les données de la couche application lorsqu'elles sont disponibles.

## Objectif du Script
L'objectif principal de ce script est de fournir une compréhension approfondie du fonctionnement du trafic réseau, en analysant les paquets à différents niveaux (Ethernet, IP, TCP, UDP, ICMP et application). Ce sniffer peut être utilisé à des fins éducatives pour apprendre le fonctionnement des protocoles réseau et pour la surveillance de la sécurité. La sortie du script est redirigé dans un fichier accessible dans le même dossier que le script.

## Version de Python
- Ce script est compatible avec Python 3.x. 

## Mentions Légales
Ce script est fourni "tel quel", sans aucune garantie d'aucune sorte. L'utilisation de ce sniffer réseau doit être conforme aux lois et réglementations locales sur la surveillance et l'analyse du trafic réseau. L'auteur décline toute responsabilité pour les dommages causés par une utilisation inappropriée.

## Requirements
Avant d'exécuter le script, assurez-vous d'avoir les éléments suivants installés :

1. **Python 3.x** : Assurez-vous d'avoir installé Python 3 sur votre système. Vous pouvez télécharger Python à partir de [python.org](https://www.python.org/downloads/).
2. **Scapy** : Vous devez installer la bibliothèque Scapy, qui peut être installée via pip. Exécutez la commande suivante :
   ```bash
   pip install scapy
3. Permissions Administratives : Le sniffer nécessite des droits d'administrateur pour capturer le trafic réseau. Assurez-vous d'exécuter le script avec les permissions appropriées (ex. : avec sudo sur les systèmes Unix).

## Usage
Pour exécuter le script, modifiez le nom de l'interface réseau dans le fichier source et lancez-le depuis le terminal :
   python sniffer.py

### Remarques
- N'oubliez pas d'adapter le nom du fichier (`sniffer.py`) si votre script a un autre nom.
- Assurez-vous d'inclure des instructions sur la manière d'exécuter le script et sur les systèmes d'exploitation pris en charge.

Si vous avez besoin de modifications supplémentaires ou d'autres sections, n'hésitez pas à demander !
