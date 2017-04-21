# LAMP-with-Docker

Déployer une stack LAMP dans des containers Docker

Pour cela, on procède en 3 étapes
  - Le code de création du container est pusher sur GitHub
  - GitHub utilise un webhook pour notifier à Jenkins qu'il y a eu u update du code
  - Jenkins récupère le repertoire GitHub concerné, build et lance notre container Docker
