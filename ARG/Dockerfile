ARG version
FROM almalinux:${version}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Shiva
ARG Duration=6-Months
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${Duration}"
CMD [ "sleep", "100" ]
