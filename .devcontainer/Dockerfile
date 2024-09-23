from mcr.docker.internal.cba/devcontainers/dotnet:1-8.0

COPY certs/* /etc/sst/certs/
ENV REQUESTS_CA_BUNDLE=/etc/sst/certs/ca.pem
ENV CA_BUNDLE=/etc/sst/certs/ca.pem
RUN update-ca-certificates