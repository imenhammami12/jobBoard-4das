# eureka-server

Serveur de découverte Eureka (Partie 1 du TP). Port **8761**.

```bash
mvn spring-boot:run
```

Dashboard : http://localhost:8761 (« No instances available » tant qu'aucun client n'est lancé).

Ordre de démarrage : eureka-server → candidat → job → (meeting, notification).
Un service peut mettre jusqu'à 30 secondes à apparaître dans le dashboard.
