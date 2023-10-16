#Wiki.js

Opdracht 1 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.
lens:
helm repo add requarks https://charts.js.wiki
helm install -f values.yaml my-release requarks/wiki --namespace wiki --create-namespace
$ helm upgrade my-release requarks/wiki -f values.yaml   
