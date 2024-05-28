# Acme dashboard.

Created to learn fundamentals of Next.js. Concepts such as server-side rendering, dynamic routing, Static and Dynamic Rendering, Streaming, server actions and Authentication etc.

![Acme full web application](https://nextjs.org/_next/image?url=%2Flearn%2Fcourse-explainer.png&w=750&q=75&dpl=dpl_Ejtt9BCyCFNeRJdBoVsM9Es9x8xe)


## Creating a new project
```bash
npx create-next-app@latest nextjs-dashboard --use-npm --example "https://
github.com/vercel/next-learn/tree/main/dashboard/starter-example"
```


## Getting Started
Follow these steps to get started with Fast-React-Pizza:

1. Clone this repository to your local machine:
```
git clone https://github.com/NikhilMandaliya/The-Wild-Oasis.git
```
2. Navigate to the project directory.
```
cd NextJS-dashboard
```
3. Install the project dependencies:
```
npm install
```
4. Start the development server:
```
npm run dev
```  
This will start the Vite development server. Let's check to see if it's working. Open http://localhost:3000 on your browser.

5. Setting Up Your Database:

We are using PostgreSQL database using `@vercel/postgres` to keep this simple.
Create project in vercel and also create database, and copy environment variables in .env file
Then you can seed database.
```
npm run seed
```


## Folder structure

- **/app:** Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.

- **/app/lib:** Contains functions used in your application, such as reusable utility functions and data fetching functions.

- **/app/ui:** Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.

- **/public:** Contains all the static assets for your application, such as images.

- **/scripts/:** Contains script files that you can use for Ex. to populate your database in a later chapter.

- **Config Files:** You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app.

- **app/lib/placeholder-data.js:** Each JavaScript object in the file represents a table in your database. For example, for the invoices table.

- **/app/lib/definitions.ts:** Here, we manually define the types that will be returned from the database.

## Try it out

You can check [live](https://nik-next-js-dashboard.vercel.app/) version of this application using the following credentials:
- Email: user@nextmail.com
- Password: 123456

---

You can check [Next.js course](https://nextjs.org/learn/dashboard-app) to learn more.

