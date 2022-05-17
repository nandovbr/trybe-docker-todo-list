FROM alpine:3.12

WORKDIR ./todo-app/front-end

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD npm start
