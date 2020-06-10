FROM node:lts

WORKDIR /

RUN git clone https://github.com/docker-hy/frontend-example-docker

WORKDIR frontend-example-docker

RUN npm install

ENV API_URL=http://localhost/api/

ENTRYPOINT ["npm"]
CMD ["start"]
