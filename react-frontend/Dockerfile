FROM node
WORKDIR /myfrontend
COPY package*.json /myfrontend
RUN npm install
COPY . . 
EXPOSE 3000
CMD ["npm","start"]
