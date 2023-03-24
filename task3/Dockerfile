FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY packages/* ./
RUN npm i --omit=dev
COPY src/* ./

EXPOSE 3032 
CMD [ "node", "main.js" ] 