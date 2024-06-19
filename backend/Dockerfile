FROM node    
WORKDIR /app
COPY . .
RUN apt-get update
RUN npm i
COPY package.json .
COPY .env.sample .env
EXPOSE 8080
CMD ["npm", "start"]

