FROM gitea/gitea:1.0

#RUN adduser git

USER git

ADD docker-entrypoint /usr/bin/docker-entrypoint
ADD app.ini /tmp/app.ini

CMD ["/bin/bash","/usr/bin/docker-entrypoint"]
ENTRYPOINT []
