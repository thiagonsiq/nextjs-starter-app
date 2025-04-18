## Sample Next.js Application

# Tech Stack

- Next.js / TypeScript
- Authentication: NextAuth.js 
- Vercel: CI/CD Deployments
- Storage: Neon Serverless Postgres (through Vercel)
- Package Manager: pnpm

# Running the Application

(if never done before, run `npm install -g pnpm` to install the package manager used in this project)

- Run `pnpm i` to install the project's dependencies
- Followed by `pnpm dev` to start the development server


# Project Structure

- /app: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- /app/lib: Contains functions used in your application, such as reusable utility functions and data fetching functions.
- /app/ui: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- /public: Contains all the static assets for your application, such as images.