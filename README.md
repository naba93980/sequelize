## Sequelize ORM

A nodejs based project exploring Sequelize, a Node.js ORM for working with relational databases.

### Overview

This repository covers Sequelize fundamentals and practical database operations, including model definitions, associations, querying techniques, transactions, and database migrations.

### Topics Covered

- **Models** — defining models and managing database entities
- **Associations** — one-to-one, one-to-many, many-to-many, and polymorphic associations
- **Querying** — Sequelize queries, raw SQL queries, and Query Interface
- **Eager and Lazy Loading** — retrieving associated data
- **Transactions** — managing transactional database operations
- **Migrations and Seeders** — managing schema changes and populating initial data
- **Model Associations** — working with related entities such as users, posts, comments, tags, images, and videos

### Project Structure

- `sequelize/` —  sequelize concepts with express controllers, routes, and models
- `migrations&seeders/` — database migrations, seeders, and model definitions
- `Notes/` — supplementary notes and TypeScript examples

### Getting Started

**Prerequisites:** Node.js, npm, nodemon, mysql database running at port 3306.

1. Clone the repository:

   ```bash
   git clone https://github.com/naba93980/sequelize.git
   cd sequelize
   ```

2. Navigate to the application:

   ```bash
   cd sequelize
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure the database connection in `connectDatabase.js` and any required environment variables.

5. Start the application using the script defined in `package.json`:

   ```bash
   node start
   ```

**Note:** The `migrations&seeders` directory is a separate example. Its database configuration and dependencies should be set up independently.

### Purpose

A practical learning reference for understanding how Sequelize abstracts relational database operations and integrates with Node.js applications.
