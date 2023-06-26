FROM node:16-alpine
WORKDIR /app/front-end
COPY . .
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm"]
CMD ["start"]
EXPOSE 3000
