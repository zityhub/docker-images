FROM google/cloud-sdk:505.0.0-alpine

RUN apk add envsubst kubectl openssl

RUN gcloud --quiet components install gke-gcloud-auth-plugin

RUN curl -fsSL https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash
