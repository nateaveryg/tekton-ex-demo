# tekton-ex-demo
## Demo Repo for creation and installation of Tekton on GCP


Configure Terraform Autopilot cluster

gcloud container clusters create-auto tekton1 \\
    --region=us-central-1 \\
    --project=end-to-end-demo-v1 

Verify the cluster

gcloud container clusters describe tekton1 \\
    --region us-central-1