ARG version
FROM almalinux:${version:-8} 
# Arg will pass the value to from. if user do not send then will pass the default value :-8 
#RUN cat /etc/*release
ARG COURSE=Docker
ARG Learner=Bhavya
ARG Duration=120HRS
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${Learner}, Duration is: ${Duration}"
CMD [ "sleep","100" ]


