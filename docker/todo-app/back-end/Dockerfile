FROM alpine:3.12

WORKDIR ./todo-app/back-end

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3001

CMD npm start
