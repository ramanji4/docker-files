ARG version
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="120 Hrs"
ENV Course=$course
RUN echo "Course: $course, duration: $duration, version: $version"
CMD ["sleep", "100"]


#ENV variables can reflect to image and container as well
#ARG is only accessed at the time of image creation
#we can use ARG before FROM instruction as to supply the version number to base image.
#the ARG instruction which mentioned before FROM, is only valid till FROM instuction only. it can't be accessed after FROM instruction
#we can access ARG variable in the container also by using ENV instruction as mentioned above