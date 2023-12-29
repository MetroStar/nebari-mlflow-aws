ARG MLFLOW_VERSION

FROM ghcr.io/mlflow/mlflow:v${MLFLOW_VERSION}

LABEL org.opencontainers.image.description="MLflow with AWS and Postgres dependencies"

# Dependencies required for AWS S3 integration
RUN pip install boto3 psycopg2-binary
