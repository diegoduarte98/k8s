- Type service ClusterIP gera IP interno.
- Type service LoadBalance gera IP externo somente em cloud provider.
- Para direcionar a porta da minha maquina para o container
    kubectl port-forward service/goserver-service 3000:3000
- Rollback version
    kubectl rollout undo deployment goserver