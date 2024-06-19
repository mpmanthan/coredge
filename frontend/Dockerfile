FROM node

WORKDIR /app

COPY . .

COPY package.json ./app

RUN npm install
#RUN npm install -g npm@10.8.1

#RUN npm install -g vite && npm install tailwindcss && npm install autoprefixer 

COPY .env.sample .env

EXPOSE 5173

CMD ["npm", "run", "dev"]


#FROM node    
#WORKDIR /app
#COPY . .
#RUN apt-get update
#COPY package*.json .
#RUN npm cache clean --force
#RUN npm install
#COPY .env.sample .env
#EXPOSE 5173
#CMD ["npm", "start"]


