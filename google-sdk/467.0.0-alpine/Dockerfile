FROM google/cloud-sdk:467.0.0-alpine

RUN apk add envsubst kubectl vim

RUN gcloud --quiet components install gke-gcloud-auth-plugin
