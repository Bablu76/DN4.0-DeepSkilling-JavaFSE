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

## Week-07

### 🔹 Task 9: `cricketapp` – ES6 Features in React

**Concepts Covered:**
- ES6 features: `map()`, arrow functions, destructuring, array merging
- Conditional rendering using a `flag` variable

**Components:**
- `ListofPlayers`: Display player name and score
- `Scorebelow70`: Filter and display players with score < 70
- `IndianPlayers`: Merged `T20Players` and `RanjiTrophyPlayers` arrays

### 🔹 Task 10: `officespacerentalapp` – JSX & Inline Styling

**Concepts Covered:**
- JSX syntax, React expressions, and JSX attributes
- Inline CSS for dynamic style (conditional rent color)

**Features:**
- Image rendering
- Object looping with JSX
- Dynamic color for rent (`red` if ≤60000, `green` if >60000)


### 🔹 Task 11: `eventexamplesapp` – Event Handling

**Concepts Covered:**
- React event handlers
- Function parameters in events
- Synthetic events

**Features:**
- `Increment` button triggers multiple functions
- `Say Welcome` button passes a custom message
- `OnPress` button demonstrates synthetic events
- `CurrencyConvertor`:
  - INR to USD/EUR conversion using `switch`
  - Uses `alert()` to display result



### 🔹 Task 12: `ticketbookingapp` – Conditional Rendering with Auth

**Concepts Covered:**
- Conditional rendering using `isLoggedIn` state
- Simple login/logout flow

**Features:**
- Guest users can view flights only
- Logged-in users can book tickets
- Components: `Greeting`, `LoginButton`, `LogoutButton`



### 🔹 Task 13: `bloggerapp` – Conditional Rendering Showcase

**Concepts Covered:**
- All 4 types of conditional rendering:
  - `if-else`
  - Ternary (`? :`)
  - Logical AND (`&&`)
  - `switch-case`

**Components:**
- `BookDetails`: Uses `&&` to conditionally render book list
- `BlogDetails`: Renders blog list using ternary logic
- `CourseDetails`: Uses `if-else` to render course data

**Layout:**
- Three-column Flexbox layout
- Vertical lines separate each section

---