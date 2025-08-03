ARG version
FROM almalinux:${version:-9} #-9 is a placeholder for the default version if version is not provided
ENV Name="sameer" \
    designation="DevOps Engineer" 
ARG experience="3"
ENV experience=${experience} #Set the ARG as an environment variable to acess it in the container
RUN echo "Name: $Name, Designation: $designation, Experience: $experience years"
CMD ["sleep", "1000"]
