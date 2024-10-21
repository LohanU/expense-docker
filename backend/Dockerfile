FROM node:20.18.0-alpine3.20
ENV DB_HOST="mysql"
EXPOSE 8080
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install 
CMD ["node","index.js"]


# Before bast practices implimented
# FROM node:20
# ENV DB_HOST="mysql"
# EXPOSE 8080
# RUN mkdir /opt/server
# WORKDIR /opt/server
# COPY package.json .
# COPY *.js .
# RUN npm install 
# CMD ["node","index.js"]