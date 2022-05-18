FROM mjgargani/puppeteer:trybe1.0 
WORKDIR /app
COPY package.json ./
ADD ./node_modules.tar.gz ./
COPY . .
EXPOSE 3001
ENTRYPOINT ["npm", "test"]

