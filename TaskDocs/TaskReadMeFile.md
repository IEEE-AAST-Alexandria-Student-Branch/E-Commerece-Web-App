# Full Stack E-Commerece Application

This is a simple e-commerce clothing application that lists products of an imaginary company, handle carts and user data persistence stuff.

### Table of Contents

-   [Phase 1](#phase-one)
    -   [User Stories](#user-stories)
    -   [Technical Details](#technical-details)
    -   [Main Outcomes](#main-outcomes)
-   [Phase 2](#phase-two)
    -   [Description](#description)
    -   [Main Outcomes](#main-outcomes-1)

## Phase One
### User Stories
- As an **admin** I want to be able to **delete** products so that I can protect my website from unsuitable content.
- As an **admin** I want to **access website revenue** in a specific month for business purposes.
- As a **seller** I want to **upload** prodoucts in the website to make customer able to see it.
- As a **seller** I want to **be notified** when a customer buy a product of mine, just for fancy purposes.
- As a **customer** I want to be able to **put products in carts** to buy it all at once.
- As a **customer** I need to **filter** displayed products by type for accessability purposes.
- As a **customer** I want to be able to **type my feedback** on a specific product if I have bought it to be displayed on public. 

### Technical details
<details>
  <summary>General</summary>
  <ul>
    <li>Your are free to choose whether to use <b>React</b> as application's frontend and <b>Express.js</b> as it's backend or to use <b>Next.js</b> as a Meta framwork</li>
    <li>You can try build this app using another tech stack that is not React-related if you already familier with it and want to use another technology</li>
    <li>Both frontend and backend teams should work together and communicate to figure out API challenges.</li>
    <li>It's your call when it comes to choosing the suitable packages.</li>
    <li>User interface <b>Must be</b> responsive.</li>
  </ul>
</details>
<details>
  <summary>Frontend</summary>
  <ul>
    <li>Atomic CSS Design is <b>Required</b></li>
    <li>Using state that lives outside components approach is <b>Required</b></li>
    <li>Clonning <a href="https://www.levelshoes.com/men/accessories.html">level shoes</a> UI design is <b>Required</b>, and for every button that handles a functionallty that is not required in this task, it is enough to clone the UI only and it is <b>your choice</b> to whether to make it functionally active and connect or not.</li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li>You are free to choose whether to use <b>SQL</b> or <b>NoSQL</b> database</li>
    <li>Api error responses handling system is <b>Required</b></li>
    <li>JWT Authentication is <b>Required</b></li>
    <li>
    Following the provided schema for each modle is <b>Required</b>
    <details>
  <summary>Schemas</summary>
 <pre>
// User
{
  "id": 0000,
  "name": "user",
  "email": "example@example.com",
  "password": "A%h8*/#hk#a",
  "role": "admin"
}
</pre>
<pre>
// Product
{
    "id": 0000,
    "name": "product",
    "type": "T-shirt",
    "price": 0000
}
</pre>
<pre>
// Cart
{
    "user_id": "product",
    "products": [
      "0000",
      "0000",
      "0000"
    ]
}
</pre> 
</details>
    </li>
  </ul>
</details>



### Main Outcomes
- Contribution between two teams (frontend and backend).
- Build a project that handles features simmiller to what are built on gournd.

## Phase Two
### Description
Convert each JS file that you have created in the first phase to TS extenstion, install types for packages that you have used in your application and user TS best practices to refactor your application.
### Main Outcomes
- Typescript best practises and resolving types errors.
- Getting ready for large scale JavaScript applications development and as most of them requires TypeScript skills.
