FROM centos

RUN yum update -y

RUN yum install npm -y

WORKDIR /app

COPY ./package.json ./

RUN npm install

COPY ./ ./

CMD ["npm","run","start"]

