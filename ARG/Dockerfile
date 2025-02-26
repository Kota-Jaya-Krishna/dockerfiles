# FROM almalinux:9
# ENV course="Devops with AWS" \
#     trainer="Jayakrishna" \
#     duration="120 hrs" 
# RUN echo "Hello ${trainer}" > /tmp/devops.txt
# CMD ["sleep", "100"]

# NOTE: ENV variables can be access at the time of image building and in container also.


# FROM almalinux:9
# ENV course="Devops with AWS" \
#     trainer="Jayakrishna" \
#     duration="120 hrs" 
# #here username is the key and some_user is default value
# ARG USERNAME=JK
# RUN echo "Hello User: ${USERNAME}"
# CMD ["sleep", "100"]



ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="Jayakrishna" \
    duration="120 hrs" 
#here username is the key and some_user is default value
ARG USERNAME=JK
RUN echo "Hello User: ${USERNAME}, image version ${version}"
CMD ["sleep", "100"]