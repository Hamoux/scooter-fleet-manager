# Scooter Fleet Manager

Application Java de gestion d'un parc de scooters, développée en binôme dans le cadre d'un projet académique orienté objet.

---

## Fonctionnalités

- **Gestion des scooters** — ajout, suppression, suivi d'état (disponible, loué, en maintenance)
- **Gestion des clients** — enregistrement, vérification du permis, historique de locations
- **Gestion des locations** — création, retour, calcul de durée
- **Parc de scooters** — vue globale du parc avec localisation et disponibilité
- **Persistance des données** — lecture et écriture dans un fichier `Data.txt`
- **Interface graphique** — affichage via Java Swing

---

## Architecture

```
scooter-fleet-manager/
├── Main.java          # Point d'entrée de l'application
├── Scooter.java       # Modèle scooter (état, marque, modèle)
├── Parc_Scooter.java  # Gestion du parc (ajout, retrait, recherche)
├── Client.java        # Modèle client (identité, permis)
├── Location.java      # Gestion des locations (création, retour)
├── Marque.java        # Entité marque
├── Modele.java        # Entité modèle de scooter
├── Permis.java        # Vérification et gestion des permis
└── Data.txt           # Fichier de persistance des données
```

---

## Stack technique

| Élément | Technologie |
|---------|-------------|
| Langage | Java |
| Interface | Java Swing |
| Modélisation | UML, Programmation Orientée Objet |
| Persistance | Fichier texte (Data.txt) |

---

## Lancement

```bash
# Compiler le projet
javac *.java

# Lancer l'application
java Main
```

---

## Auteurs

- Hamou Djellab
- Lounes Medjbour
