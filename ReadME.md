27.04.2021
	
CCI

Github connection created on Azure Devops
Container registry will not be separated as non-prod/prod. We can create folders/tags to manage it in one registry.
Azure Container Registry will not be injected to AKS, Kubernetes image pull secret will be used

SWO

JFrog / Nexus / Harbor solutions will be examined to manage containers, binary resources etc.
SoftwareOne will make a research about how to split container registries for environments / projects etc. 
How to keep helm charts? https://docs.microsoft.com/en-us/azure/container-registry/container-registry-helm-repos

CI/CD provided by Azure Devops tool and developments will made as source control independent?
Azure Key Vault will be used for example keeping container registry access token
How can we provide and automate semantic versioning?
Helm chart will write for CDP. Service project