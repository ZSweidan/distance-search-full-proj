FROM node:12
WORKDIR /app
COPY ["package.json", "package-lock.json", "./"]
RUN npm ci 
COPY . /app
EXPOSE 3000
CMD ["npm", "start"]