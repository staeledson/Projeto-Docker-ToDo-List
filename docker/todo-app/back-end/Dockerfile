FROM node:14

WORKDIR /usr/src/todo-app/back-end

EXPOSE 3001

ADD node_modules.tar.gz ./

COPY ./ ./

ENTRYPOINT ["npm", "start"]
