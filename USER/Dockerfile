FROM almalinux:9
RUN dnf install git -y
RUN useradd suraj

USER suraj
CMD ["google.com"]
ENTRYPOINT ["ping"]
# This Dockerfile sets up a user named 'suraj' and uses ENTRYPOINT to run