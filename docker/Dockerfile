FROM ubuntu:trusty

ADD install-refine.sh install-refine.sh
RUN chmod +x install-refine.sh
RUN ./install-refine.sh

EXPOSE 3333

CMD ["/start.sh"]