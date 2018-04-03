FROM  jenkins/jenkins:lts

# creo un archivo con el nombre del plug-in que me interesa
RUN echo 'github-organization-folder' > /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt


#RUN git clone https://github.com/mauricio-salinas/courses-devops-project-java-dogs.git

#WORKDIR courses-devops-project-java-dogs

#RUN ./gradlew build

#EXPOSE 8083

#CMD SERVER_PORT=8080 ./gradlew bootRun

CMD /usr/local/bin/jenkins.sh
