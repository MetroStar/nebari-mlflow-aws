ARG MLFLOW_VERSION

FROM ghcr.io/mlflow/mlflow:v${MLFLOW_VERSION}

# Dependencies required for AWS S3 integration
RUN pip install boto3 psycopg2-binary
