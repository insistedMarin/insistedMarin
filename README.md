# Welcome to My GitHub!

## About Me

I'm a passionate software developer specializing in web development and cloud technologies.

## Skills

- **Programming Languages**: Java, JavaScript, Python, Go
- **Frameworks**:Spring Boot, Angular, React, Django
- **Tools**: Docker, Kubernetes, AWS

## My Work

- [AI Image search engine](https://github.com/insistedMarin/Image-Search-System-Using-CLIP-Model)
  
  Construct Open AI's **CLIP** model into a docker image, and use it to construct an image search engine, using a cloud-native development method. My model image is public and everyone is welcome to use it.
  This system mainly demonstrates the basic architecture of an AI-based image search engine. If it is a production environment, please use a vector search engine for optimization, such as **Elastic Search**, **Faiss**.
  
- [Trading System](https://github.com/insistedMarin/Transaction-Spring)

  A real-time trading system that taught me a lot. **Spring Cloud** is used to implement the microservice architecture,**kafka** message queue implements decoupling between services, **redis** implements transaction snapshots, API gateway implementation, websocket implements server message push, and we can write our own ORM framework.

- [Online Reading](https://github.com/insistedMarin/online-reading)

  An online library sounds very cool, but what is more interesting is that this project will let us learn more, how to quickly search documents? ElasticSearch is undoubtedly the first choice. The flashback indexing mechanism allows us to quickly find relevant documents through keywords. The only problem is, it's too heavy (local deployment puts my laptop through the paces). Fortunately, we can experience **Elastic Cloud** for 7 days to explore Elastic Search and **Kibana**. As well as **logstash** and **various connectors** to ensure data synchronization.

- [Spark ETL](https://github.com/insistedMarin/Spark-Scala-String-Scalarization)

  **Spark** is a very important framework for data engineering and is divided into two versions: **python** and **scala**. The new version of Spark already supports the use of **dataframes**, so it is not difficult for people who are familiar with Pandas to get started. This project gave me more experience in various deployment methods. To deploy in an AWS environment we can use **EKS** and **EMR**, as well as **Glue** if you want to develop directly with pySpark. It should be noted that EMR cannot configure virtual machines, but directly submits project packages, so the project cannot contain operations that interact with the operating system.

## Open Source Contributions

- [incubator-answer](https://github.com/insistedMarin/incubator-answer) 

  A very popular Apache incubator open source project, a few months ago I started trying to contribute to the open source project. I am very happy to choose this project as the first open source project I contributed to. The project's workflow is very **standardized** and the community members are **friendly**, which allowed me to learn a lot about **code specifications** and **architectural design**. This project is a typical web project with separate front and back ends, developed using **React** and **Golang**. Golang, as the current main language for cloud native development, has given me a good experience. If you are already proficient in Java, C, and Python, learning Golang will be very fast. And the backend adopts the **MVC** architecture (the framework Gin itself is a lightweight framework, so there is no MVC architecture, but the project manually implemented the architecture. There are many such examples. The MVC architecture does a great job in service decoupling and code clarity. Still very good), so it’s not difficult to get started.


## Contact Me

- Email: [xyyr190304@gmail.com](mailto:xyyr190304@gmail.com)


