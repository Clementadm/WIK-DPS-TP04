# TP4 DevOps

Afin de lancer notre pod

```
kubectl apply -f podTp.yaml
```

```
kubectl port-forward service/echo-service 8080:8080
```

Rajouter à son fichier \etc\host le nom de domaine suivant `production.app.fr` lié à son localhost

Se rendre sur l'url `http://production.app.fr:8080/ping` afin de vérifier que la requete est bien affichées.
