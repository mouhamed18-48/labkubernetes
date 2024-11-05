Pour tester l'application apres avoir recuperer les dossiers en local vous devez lancer docker ensuite lancer le commande "minikube start --nodes 3 --driver=docker" pour executer minikube.
Ensuite vous vous deplacer a l'interieur du dossier avec le terminal lancer le commande "kubectl apply -f manifests" pour  déployer et mettre à jour les ressources dans le cluster Kubernetes à partir des fichiers de manifestes YAML
et enfin "kubectl get pods" pour avoir la  liste de tous les Pods actuellement en cours d'exécution dans le cluster Kubernetes.
