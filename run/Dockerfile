FROM flossy:base

RUN mkdir /root/.vnc /root/config 

ADD  passwd   /root/.vnc/passwd
ADD  xstartup /root/.vnc/xstartup
ADD  fvwm2rc  /root/config/fvwm2rc
COPY startup.sh /

CMD ["/bin/bash", "/startup.sh"]