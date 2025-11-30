FROM almalinux:9
RUN dnf install telnet net-tools ip-utils bind-utils -y
RUN useradd roboshop
USER roboshop
CMD [ "sleep" , "10000" ]