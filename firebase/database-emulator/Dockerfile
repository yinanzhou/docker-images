FROM eclipse-temurin:17-alpine

RUN apk update && apk add nodejs npm
RUN npm install -g firebase-tools
RUN java -version && node -v && npm -v && firebase --version
RUN firebase setup:emulators:database
