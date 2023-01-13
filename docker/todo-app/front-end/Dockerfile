FROM node:14

WORKDIR /usr/src/todo-app/front-end

EXPOSE 3000

ADD node_modules.tar.gz ./

COPY ./ ./

ENTRYPOINT ["npm", "start"]
