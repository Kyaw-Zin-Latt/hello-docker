FROM node:19.8.1-alpine3.17
WORKDIR /app
COPY . .
ADD . .
RUN npm install
ENV API_URL=http://api.myapp.com/
EXPOSE 3000
CMD ["npm", "start"]
