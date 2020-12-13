FROM node:12.18-alpine
ENV dburl=mydurl \
    user=myusr \
    srcdir=/usr/src/app
WORKDIR ${srcdir}
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "npm","start" ]