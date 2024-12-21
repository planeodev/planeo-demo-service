# planeo-demo-service
This is a helm chart that runs a demo service on port `:8080`

## requirements
- a working `kubernetes` cluster
- a configured `kubectl` CLI
- a `helm` client installed on your machine

## usage
`helm install demo-service ./charts/demo-service --namespace demo-service --create-namespace`

## license
See [LICENSE](https://github.com/planeodev/planeo-demo-service/blob/master/LICENSE) for full details
