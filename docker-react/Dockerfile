FROM node:18.14.0-alpine
WORKDIR /docker-react
ENV PATH="./node_modules/.bin:$PATH"
COPY . .
RUN npm run build
CMD ["npm", "start"]