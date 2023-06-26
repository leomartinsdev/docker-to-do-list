FROM node:16-alpine
WORKDIR /app/back-end
COPY . .
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm"]
CMD ["start"]
EXPOSE 3001
