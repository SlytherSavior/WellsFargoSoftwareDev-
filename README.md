# Financial Advisor Management System

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-%2300C7B7.svg?style=for-the-badge&logo=hibernate&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Project Overview

This repository contains the backend implementation for the Financial Advisor Management System, developed as part of the Wells Fargo SWE simulation on Forage. The system is designed to manage financial advisors and their clients, including the management of client portfolios and securities.

### Features

- **Entity Modeling:** Implemented the data model using Java Persistence API (JPA) to map Java objects to relational database tables.
- **Spring Boot:** Utilized the Spring Boot framework for creating a robust and scalable backend application.
- **Relational Database:** Data is persisted using MySQL, ensuring reliable and consistent data storage.
- **ORM with JPA:** Leveraged JPA annotations to simplify database interactions and focus on business logic.
- **Development Tools:** Developed using Eclipse IDE and Visual Studio Code for a seamless and efficient development process.

### Entity Relationship Diagram (ERD)

The data model includes the following key entities:
- **Financial Advisor**: Manages clients and their portfolios.
- **Client**: Each client has a portfolio managed by a financial advisor.
- **Portfolio**: Contains one or more securities belonging to a client.
- **Security**: Represents a financial asset within a client's portfolio.

![ERD](./FINAL%20ERD%20.jpg)

### Project Structure

### Project Structure

- .git
- .nvm
- .gitignore
- pom.xml
- src
  - main
    - java
      - com
        - slyther
          - practice            
            - entities
              - FinancialAdvisor.java
              - Client.java
              - Portfolio.java
              - Security.java
            - entrypoint.java
- target

## Future Enhancements

- **Frontend Integration:** Add a React-based frontend to provide a user-friendly interface for managing financial advisors, clients, portfolios, and securities.
- **Authentication & Authorization:** Implement security features to ensure that only authorized financial advisors can access and modify client information.
- **Performance Optimization:** Explore caching strategies and database indexing to improve the performance and scalability of the system.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Acknowledgments

This project was developed as part of the Wells Fargo SWE simulation on Forage. Special thanks to Wells Fargo and Forage for providing this learning opportunity.

## Contact

For any inquiries or contributions, please contact me via [LinkedIn](www.linkedin.com/in/slyther) or [email](mailto:shrijan5414@gmail.com) or [X/Twitter](https://x.com/SlytherShrijan).
