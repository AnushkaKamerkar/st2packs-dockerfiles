FROM alpine:3.8

ONBUILD VOLUME ["/opt/coditation/packs", "/opt/coditation/virtualenvs"]

# Copy packs and virtualenvs
ONBUILD COPY --from=builder /opt/coditation/packs /opt/coditation/packs
ONBUILD COPY --from=builder /opt/coditation/virtualenvs /opt/coditation/virtualenvs
