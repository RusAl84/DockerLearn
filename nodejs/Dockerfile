FROM node # с какого image хотим сделать свой
WORKDIR /app # контекст проекта
COPY . . # копируем из локального проекта
EXPOSE 3000 # какой порт запускается
RUN npm install # запускаем команду когда собирается образ
CMD ["node", "test.js"] # запускаем команду, когда запускается образ