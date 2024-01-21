FROM quay.io/keycloak/keycloak:22.0.5
LABEL version="1.0"
LABEL description="Custom Keycloak 22 Image"
WORKDIR /opt/keycloak
RUN /opt/keycloak/bin/kc.sh build
ENTRYPOINT ["/opt/keycloak/bin/kc.sh"]