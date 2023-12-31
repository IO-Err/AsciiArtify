### ArgoCD installation

### Prepare cluster:
For demo, single node cluster will be configured:
`k3d cluster create app-demo`

Create namespace:
`kubectl create namespace argocd`

Install  ArgoCD with default configuration:
`kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml`

Forward port to acces WebUI:
`kubectl port-forward svc/argocd-server -n argocd 8080:443 2&>1 > /dev/null &`

Get initial password for `admin` user:
`kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}"|base64 -d; echo`
