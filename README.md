# Lab for TLS Setup for AGIC on aks
1. Enable AGIC via addon
2. Craete application deployments
3. Deploy certmanager and create cluster issuer
4. Link the dns hostanme with public ip of application gateway
5. Create ingress with cluster issuer details 
6 Check the status of Tls certificates and cluster issuer, once it becomes true. You can access the application using the https://url

Reference: https://learn.microsoft.com/en-us/azure/aks/ingress-tls?tabs=azure-cli#use-tls-with-lets-encrypt-certificates




