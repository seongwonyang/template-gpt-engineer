Let the GPT Engineer generates code:
```
cd gpt-engineer
docker-compose up
```

After generating code successfully you can see the files in your microservices folder.
And you can run them with:

```
cd {microservice}
mvn spring-boot:run
```

> Note: Ensure to use JDK 17:
```
sdk install java 17.0.4.1-tem
```

