ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with Docker" \
    module="Dockerfiles" 

ARG topic="topic is arg"
ENV topic=$topic
RUN echo "Hi, Course is: ${course}, topic is: ${topic}"
CMD ["sleep", "1000"]
# This Dockerfile demonstrates the use of ARG instruction to define build-time variables.