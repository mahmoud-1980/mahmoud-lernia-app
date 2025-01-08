FROM registry.access.redhat.com/ubi9:latest AS builder

RUN dnf install -y git-core golang make
RUN git clone https://github.com/mahmoud-1980/mahmoud-lernia-app.git


FROM registry.access.redhat.com/ubi9-minimal:latest
COPY --from=builder /lernia-app/src/lernia /lernia
CMD ["/lernia"]
