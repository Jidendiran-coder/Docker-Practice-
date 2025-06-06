FROM node:22-alpine
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
ENV PORT=3001
ENV MONGO_URI=mongodb+srv://joel:pjwOUfAbRdSGy7OU@cluster-mern.c0kcm.mongodb.net
EXPOSE 3001
CMD ["node", "index.js"]

