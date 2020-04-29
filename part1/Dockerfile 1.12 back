FROM node:lts

WORKDIR /

RUN git clone https://github.com/docker-hy/backend-example-docker

WORKDIR backend-example-docker

RUN npm install

#there was no way i cold get this to work with the front end url.
#i tried localhost, localhost:5000, http://localhost, http://localhost:5000...
#this was the solution i found
ENV FRONT_URL=*

ENTRYPOINT ["npm"]
CMD ["start"]
