FROM mcr.microsoft.com/devcontainers/base:jammy

RUN apt-get update && apt-get install -y \
    git \
    python3 \
    python3-pip

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Expose the application's port
EXPOSE 8000