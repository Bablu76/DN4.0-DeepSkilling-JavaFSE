# DN4.0-DeepSkilling-JavaFSE

## Week-01

### 🔸 Design Patterns & Principles
- Introduction to SOLID principles
- Types of Design Patterns (Creational, Structural, Behavioral)
- Real-world use cases
- Hands-on exercises on Factory, Singleton, etc.

### 🔸 Data Structures & Algorithms
- Time complexity analysis (Big-O notation)
- Collections framework overview
- Recursion and its applications
- Hands-on coding problems and implementation

## Week-02

### 🔸 PL/SQL
- Functions, Procedures, Cursors (reusable logic)
- Triggers (before/after)
- Hands-on with database tasks

### 🔸 JUnit5 & Mockito
- Parameterized tests
- Exception testing
- Mock DB and API calls
- Unit testing best practices

### 🔸 SLF4J Logging
- Parameterized logging
- Clean and readable logs

## Week-03

### 🔸 Spring Core
- Understanding IoC and DI
- Constructor & Setter Injection
- Spring Beans and XML-based configuration
- Hands-on Spring container setup

### 🔸 Maven
- Dependency management
- Creating and managing Maven projects
- Adding plugins and dependencies
- Project build lifecycle and structure

### 🔸 JPA, Hibernate, Spring Data JPA
- ORM concepts and annotations
- Hibernate vs JPA vs Spring Data JPA
- Entity-Relationship mapping
- CRUD operations using Spring Data
- Repository abstraction and derived queries

## Week-04

### 🔸 Spring Boot Setup

- Created Spring Boot project with Maven and embedded Tomcat

### 🔸 Spring Core with XML

- Configured beans using `country.xml` and explored ApplicationContext

### 🔸 RESTful Services – Hello World

- Built a simple `@RestController` that returns a string response

### 🔸 REST API – Static Country Response

- Returned hardcoded `Country` bean as JSON via REST endpoint

### 🔸 REST API – Dynamic Country Lookup

- Handled path parameters using `@PathVariable` and returned matched country

### 🔸 JWT Authentication Service

- Built `/authenticate` to return JWT token using Basic Auth and `jjwt` library

## Week-05

### 🔸 Spring Boot Microservice Creation

* Scaffolded standalone Spring Boot projects for Account and Loan services

### 🔸 Service Discovery with Eureka

* Set up a Eureka Server and registered microservices as Eureka clients

### 🔸 API Gateway with Spring Cloud Gateway

* Configured routes and predicates in `application.yml` to proxy calls to backend services

### 🔸 Routing & Filters

* Implemented pre‑ and post‑filters in the gateway for logging and header enrichment

### 🔸 Circuit Breaker Pattern

* Added Resilience4j (via Spring Cloud Circuit Breaker) to wrap service calls with fallback methods

### 🔸 Running Multiple Services

* Launched Account (port 8080), Loan (port 8081), Eureka (port 8761), and Gateway (port 8082) concurrently in Eclipse console tabs

## Week-06

### 🔹 Task 1: React SPA & Environment Setup
- Created a basic React project using `create-react-app`
- Displayed static welcome message
- Understood SPA vs MPA, Virtual DOM, JSX

### 🔹 Task 2: Class-Based Components
- Created a Student Management app with `Home`, `About`, and `Contact` class components
- Used `constructor()` and `render()` methods

### 🔹 Task 3: Functional Components & Props
- Developed `CalculateScore` function component
- Passed student data as props
- Used external CSS (`mystyle.css`) for styling

### 🔹 Task 4: Component Lifecycle Hooks
- Fetched API data using `componentDidMount()`
- Handled errors with `componentDidCatch()`
- Displayed post titles and bodies using state and `.map()`

### 🔹 Task 5: CSS Modules & Inline Styling
- Styled `CohortDetails` using `CohortDetails.module.css`
- Applied conditional inline styles for dynamic headings
- Scoped styles using CSS Modules

### 🔹 Task 6: React Router with Dynamic URL Params
- Set up client-side routing using `react-router-dom`
- Created `Home`, `TrainerList`, and `TrainerDetail` components
- Passed trainer ID via URL and retrieved using `useParams()`
- Rendered dynamic data from mock trainer model
