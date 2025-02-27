FROM almalinux:9
ENV course="devops with aws"\
    trainer="sivakumar"\
    duration="120hrs" 
#here user1 is key , someone is default value
ARG ${username:-some_user}
RUN echo "hello ${username}" > /tmp/devops.txt 
CMD ["sleep" , "100"] 