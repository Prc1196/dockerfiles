ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS"\
    tariner="siva kumar reddy"\
    duration="120hrs"
#here username is a key ,some_user is default value
ARG USERNAME=pradeep
RUN echo "Hello user : ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]
