FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/src/todo-app/tests

ADD node_modules.tar.gz ./

COPY ./ ./

ENTRYPOINT ["npm", "test"]