FROM google/cloud-sdk:467.0.0-alpine

RUN apk add envsubst

RUN gcloud --quiet components install gke-gcloud-auth-plugin kubectl
