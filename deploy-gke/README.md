<!-- BEGIN_ACTIONS_HEADER -->
# Deploy to GKE
<!-- END_ACTIONS_HEADER -->

<!-- BEGIN_ACTIONS_DESCRIPTION -->
Deploys a Docker image to Google Kubernetes Engine
<!-- END_ACTIONS_DESCRIPTION -->

<!-- BEGIN_ACTIONS_INPUTS -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| cluster_name | Google Kubernetes Engine Cluster Name | `""` | true
| location | Google Kubernetes Engine Cluster Location | `""` | true
| project_id | Google Cloud Platform Project ID | `""` | true
| rollout_status_wait | Wait for rollout to complete | `""` | false
| service_account_key | Google Service Account Key | `""` | true
| template_path | Path to the template file | `"kube.template.yml"` | false
| vars | Dictionary of variables to pass to the template | `""` | false
<!-- END_ACTIONS_INPUTS -->

<!-- BEGIN_ACTIONS_OUTPUTS -->
## Outputs

| Name | Description |
|------|-------------|
<!-- END_ACTIONS_OUTPUTS -->
