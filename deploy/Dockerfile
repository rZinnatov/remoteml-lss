FROM mhart/alpine-node:10
COPY . .
RUN npm install
CMD npm start
STOPSIGNAL SIGINT
EXPOSE 80