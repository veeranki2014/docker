### ARG is used to supply the variables at the time of image creation or docker build time.
ARG VERSION
FROM almalinux:${VERSION:-8}
ARG GREETINGS
RUN echo "${GREETINGS}"
RUN echo "${VERSION}"
