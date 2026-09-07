
#base image

FROM alpine/java:22-jdk 

#working directory

WORKDIR /app

#cpy the source file
COPY src /app


RUN javac -d . ToDoList.java

CMD ["java","todolist.ToDoList"]
