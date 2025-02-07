FROM nginx:mainline

RUN apt-get update && apt-get install -y --no-install-recommends \
    curl \
    ca-certificates \
    bash \
    bash-completion \
    jq \
    wget \
    vim \
 && rm -rf /var/lib/apt/lists/*
