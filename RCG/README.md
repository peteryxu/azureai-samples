# level 1

## verify az access

- az storage account list
- az storage account keys list -g MyResourceGroup -n MyStorageAccount
- az storage account keys list --account-name staistudio11046512515952
- az storage blob list  --account-key wTkQfC9TayFw9eoYGfsgI8nVqADfR6JuV6CzC3QC5f+OiHd4fl7nzHiq3+9vAUVJQ/7N4Q12yZxD+ASt9PAcYg== --account-name staistudio11046512515952 --container-name mycontainer

## api version

POST https://{your-resource-name}.openai.azure.com/openai/deployments/{deployment-id}/completions?api-version={api-version}



https://learn.microsoft.com/en-US/azure/ai-services/openai/reference

