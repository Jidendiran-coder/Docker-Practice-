FROM node:22-alpine
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
ENV PORT=3001
ENV MONGO_URI=mongodb+srv://admin:admin@cluster0.zqyqy.mongodb.net/myFirstDatabase?retryWrites=true&w=majority&appName=Cluster0
EXPOSE 3001
CMD ["node", "index.js"]

