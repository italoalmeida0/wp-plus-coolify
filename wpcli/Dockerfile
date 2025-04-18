FROM wordpress:cli
RUN apk add --no-cache unzip rsync
COPY scripts/ /usr/local/bin/
RUN chmod +x /usr/local/bin/wp-restore /usr/local/bin/wp-domain
ENTRYPOINT ["bash"]
