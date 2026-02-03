FROM debian:12

RUN apt-get update && apt-get install -y \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY . .

CMD ["/bin/bash"]