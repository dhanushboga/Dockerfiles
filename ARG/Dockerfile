ARG version
FROM almalinux:${version:-9}
ENV course="devops with aws" \
    trainer="sivakumarreddy" \
    duration="120 hrs"

ARG USERNAME=dhanush
RUN echo "hello user: ${USERNAME},image version: ${version}" > /tmp/hello.txt
CMD ["sleep","100"]