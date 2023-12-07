FROM scratch as app
LABEL org.opencontainers.image.source "https://github.com/SaimonWoidig/gh-actions"
EXPOSE 8080
WORKDIR /
COPY backend /backend
ENTRYPOINT [ "/backend" ]