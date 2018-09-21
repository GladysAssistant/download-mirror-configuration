FROM node

RUN npm install -g hypercored

EXPOSE 3282
EXPOSE 8887

VOLUME feeds

WORKDIR feeds

CMD ["hypercored"]