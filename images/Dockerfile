FROM node:19
WORKDIR "/app"
COPY ./www/package.json ./
RUN npm install
COPY ./www .
CMD ["npm", "run", "dev"]
