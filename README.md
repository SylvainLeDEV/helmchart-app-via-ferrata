# helmchart-app-via-ferrata

This Helm chart is designed to be generic and reusable for various projects and environments. It provides templates for common Kubernetes resources such as deployments, services, and ingresses without specifying particular values.

## Configuration

Environment-specific values should be managed via ArgoCD. This Helm chart is designed to be as generic as possible, meaning most specific configurations (such as environment variables, secrets, ports, etc.) should be defined in ArgoCD value files.

## Customization

To customize this Helm chart for your own application, you can:

Modify the templates to include additional Kubernetes resources if needed.

Add default values in the values.yaml file if certain configurations should be set by default.

Use ArgoCD to manage environment-specific values.