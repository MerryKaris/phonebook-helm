```bash
helm repo add phonebook-helm-repo https://raw.githubusercontent.com/MerryKaris/phonebook-helm/main
helm install phonebook2-app phonebook-helm-repo/phonebook-chart
```
- To use own images execute as below:
```bash
helm install phonebook-app phonebook-repo --set webserver_image=<image-name> --set resultserver_image=<image-name>
