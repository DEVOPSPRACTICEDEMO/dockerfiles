FROM almalinux:9
ENV course = "DevOps with Docker" \
    module = "Dockerfiles"  
ARG topic = "ARG" \
    description = "This Dockerfile demonstrates the use of ARG instruction to define build-time variables." \
    author = "DAWS" \
    version = "1.0"
RUN echo "Hi, Course is: ${course}, topic is: ${topic}" > /tmp/arg-demo.txt && 
CMD ["sleep", "1000"]
# This Dockerfile demonstrates the use of ARG instruction to define build-time variables.