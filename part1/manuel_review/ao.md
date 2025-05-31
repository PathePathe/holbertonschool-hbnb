flowchart TD
    AO[Appel d'Offres]
    Clients[Clients]
    Partenaires[Partenaires]
    References[Références]
    Formulaires[Types de formulaires]
    Fichiers[Fichiers/Livrables]
    Utilisateurs[Utilisateurs/Rôles]
    Taches[Tâches/Statuts]
    Interface[Interface Utilisateur]
    Workflow[Workflow Automatisé]
    Reporting[Reporting/Exports]

    AO -->|lié à| Clients
    AO -->|lié à| Partenaires
    AO -->|lié à| References
    AO -->|lié à| Formulaires
    AO -->|lié à| Fichiers
    AO -->|lié à| Taches
    Utilisateurs -->|accès à| Interface
    Interface -->|contrôle| Workflow
    Workflow -->|alimente| Reporting
    Fichiers -->|centralisé dans| Interface
