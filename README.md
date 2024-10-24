# Rule-Engine-with-AST
This application is a powerful rule engine designed to determine user eligibility based on various attributes such as age, department, salary, and experience. By leveraging an Abstract Syntax Tree (AST), the engine represents and manages complex conditional rules, allowing for the dynamic creation, combination, and evaluation of rules. The AST structure provides flexibility and efficiency in rule processing, making it easy to handle changing business logic and scenarios in real time.

![Rule-Engine-with-AST](https://github.com/vaibhavi-roy/Rule-Engine-with-AST/blob/main/rule1.png)
![Rule-Engine-with-AST](https://github.com/vaibhavi-roy/Rule-Engine-with-AST/blob/main/rule2.png)
![Rule-Engine-with-AST](https://github.com/vaibhavi-roy/Rule-Engine-with-AST/blob/main/rule3.png)
![Rule-Engine-with-AST](https://github.com/vaibhavi-roy/Rule-Engine-with-AST/blob/main/rule4.png)
![Rule-Engine-with-AST](https://github.com/vaibhavi-roy/Rule-Engine-with-AST/blob/main/rule5.png)
---

## Features
- **Dynamic Rule Creation**: Create, combine, and evaluate rules in real time.
- **AST-Based Architecture**: Provides flexibility and efficiency in processing complex conditional logic.
- **Scalable and Adaptable**: Easily adapt to new business logic without rewriting core functionalities.
- **User Attribute-Based Eligibility**: Process attributes such as age, department, salary, and experience.

---

## Prerequisites
- **Node.js** v14.x or later
- **npm** v6.x or later
- **MongoDB** v4.x (for storing user and rule data)
- Other dependencies as listed in `package.json`

---

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vaibhavi-roy/Rule-Engine-with-AST.git
   cd Rule-Engine-with-AST
   ```
2. **Install Dependencies**

   ```bash
   npm install
   ```
   
3. **Start MongoDB**

   Ensure that MongoDB is running on your local machine:

   ```bash
   mongod
   ```

4. **Start the Server**

   ```bash
   nodemon server.js
   ```
5. **Set up .env file**

   ```bash
   MONGODB_URI='your uri'
   ```
6. **Start the application**

   ```bash
   npm start
   ```

# Usage
To define and evaluate rules based on user attributes, the following endpoints are available:

1. Create a Rule:
POST /api/rules
- Define rules based on attributes (age, department, etc.).
- Rules are stored and processed in AST format.

2. Evaluate Eligibility:
POST /api/evaluate
- Input user data to evaluate their eligibility against the defined rules.

3. List All Rules:
GET /api/rules
-Retrieve a list of all stored rules.

# Github Repository

The source code, build scripts, and configurations are hosted on Github. All development activity, including version control, branches, and pull requests, is managed through the repository.

- Repository URL: https://github.com/vaibhavi-roy/Rule-Engine-with-AST

# Live Website

- Link: https://rule-engine-with-ast-o9k0.onrender.com/



