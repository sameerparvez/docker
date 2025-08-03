ARG version
#-9 is a placeholder for the default version if version is not provided
FROM almalinux:${version:-9} 
ENV Name="sameer" \
    designation="DevOps Engineer" 
ARG experience="3"
#Set the ARG as an environment variable to acess it in the container
ENV experience="${experience}" 
RUN echo "Name: $Name, Designation: $designation, Experience: $experience years"
CMD ["sleep", "1000"]
