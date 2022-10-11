FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/tests

ADD node_modules.tar.gz ./

COPY . /todo-app/tests/

CMD ["npm", "test"]