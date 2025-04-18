## Thiago's Development Playground

This is my website.

My goal is to use it in various ways. I'd like to: 
1. Display my professional experience, a web version of my resume so to speak
2. A technical playground of sorts, where I try new technology, frameworks, into a production environment for fun
3. Lastly, as a place to post about things I enjoy, like hobbies, trips, family, and maybe more

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