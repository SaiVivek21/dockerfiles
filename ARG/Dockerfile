ARG vesrion 
FROM almalinux:${version:-9}
ENV course="devops with aws"\
    trainer="sivakumar"\
    duration="120hrs" 
#here user1 is key , someone is default value
ARG USERNAME=sivakumar
RUN echo "hello user: ${USERNAME}, image version: ${version}"" > /tmp/devops.txt
CMD ["sleep","100"]