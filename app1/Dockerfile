FROM openjdk:11

RUN mkdir /app
WORKDIR /app
COPY spb_crud.jar /app/app.jar
COPY start.sh /app/start.sh
RUN chmod +x /app/start.sh

CMD ["/app/start.sh"]
