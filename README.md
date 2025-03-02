# CS-465
Architecture

#### Comparison of Frontend Development Approaches
In the full-stack project, two different frontend development approaches were used: one with Express, HTML, and JavaScript, and the other with a single-page application (SPA) built with Angular. The Express-based portion of the site utilized JavaScript and Express to create routes and controllers that handled browser requests. Express either served static HTML pages or dynamically generated pages using Handlebars templates populated with data from the database. These technologies worked together to process server requests and return responses to the frontend client.

The Angular-based SPA functioned differently. Upon the initial page load, the entire SPA was sent to the client, where all rendering and execution occurred within the browser. Backend calls were only required for retrieving data from the database. Unlike Express, which made frequent server calls for each page load or refresh, the SPA had a longer initial load time but allowed for seamless navigation between pages without additional requests to the server.

#### Choice of NoSQL MongoDB Database
MongoDB was chosen for its scalability and efficient querying capabilities. Its document-based structure aligns well with JSON formatting, making it a suitable choice for integration with frontend applications.

### Functionality

#### JSON vs. JavaScript and Their Role in Full-Stack Development
JSON is a data format specification that can be used across multiple programming languages, whereas JavaScript is a programming language that utilizes JSON to define objects. APIs serve as the bridge between the frontend and backend, using JSON to send and receive requests and responses in a RESTful architecture.

#### Refactoring for Improved Functionality and Efficiency
One example of code refactoring to enhance functionality was replacing static HTML pages with Handlebars templates. This change allowed for page structure reuse while enabling dynamic content updates. Another improvement involved moving content data from static JSON files within the codebase to MongoDB. This transition made it possible to modify content without requiring code redeployment.

### Testing

#### Understanding API Methods, Endpoints, and Security in Full-Stack Applications
HTTP methods define the types of interactions a client can have with a server. Common methods include GET (retrieve data), POST (create new data), PUT (update existing data), and DELETE (remove data). API endpoints serve as access points for these interactions.

Security measures in this full-stack application included user authentication and JWT-based authorization, ensuring that only authenticated users could access protected endpoints.

### Reflection

#### Course Impact on Professional Goals
This course expanded my knowledge of full-stack development and introduced me to new technologies such as Express. In my professional experience as a full-stack developer, I have worked primarily on existing projects. This course provided insight into building a full-stack application from the ground up, enhancing my understanding of how different components interact.

#### Skills Gained and Career Marketability
My JavaScript proficiency has improved significantly through hands-on practice. Additionally, I gained experience with Node.js and Express for backend development. Since Node.js is frequently listed as a required or preferred skill in job postings, acquiring foundational knowledge in this area enhances my career prospects.

