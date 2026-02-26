name: Demande de soutien
description: Créer un ticket de soutien pour le service Fortune Cookie API
title: "[SUPPORT] "
labels:
  - "[TICKET]"

body:
  - type: dropdown
    id: type_demande
    attributes:
      label: Type de demande
      options:
        - Incident
        - Demande de service
        - Question
        - Amélioration
    validations:
      required: true

  - type: dropdown
    id: impact
    attributes:
      label: Impact
      options:
        - Élevé
        - Moyen
        - Faible
    validations:
      required: true

  - type: dropdown
    id: urgence
    attributes:
      label: Urgence
      options:
        - Élevée
        - Moyenne
        - Faible
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Description
      description: Décrire clairement le problème ou la demande.
    validations:
      required: true

  - type: textarea
    id: etapes_reproduction
    attributes:
      label: Étapes pour reproduire
      description: |
        1.
        2.
        3.
    validations:
      required: false

  - type: textarea
    id: resultat_attendu
    attributes:
      label: Résultat attendu
      description: Ce qui devrait normalement se produire.
    validations:
      required: false

  - type: textarea
    id: resultat_obtenu
    attributes:
      label: Résultat obtenu
      description: Ce qui se produit réellement.
    validations:
      required: false

  - type: input
    id: date_heure
    attributes:
      label: Date et heure
      description: Indiquer quand le problème est survenu.
    validations:
      required: false
