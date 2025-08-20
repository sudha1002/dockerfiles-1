ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120hrs" \
    trainer="sivakumar reddy"
ARG USERNAME=sivakumar   
RUN echo "hello user: ${USERNAME}, image version: ${version}" > /tmp/dev.txt
CMD ["sleep","100"] 
