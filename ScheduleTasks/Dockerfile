FROM ubuntu
WORKDIR /app
COPY ./ScheduleTasks appsettings.json /app/
RUN chmod +x /app/ScheduleTasks && apt update && apt install libicu-dev libssl-dev -y
EXPOSE 7777
CMD ["/app/ScheduleTasks"]