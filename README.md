# Bryan Acido

Hi, I'm **Bryan Acido.**
I'm a Web Developer and Marketing Consultant based in Cavite, PH specializing in building websites and marketing.
Have a project you'd like to discuss? Let's chat bryanacido@gmail.com

## Getting Started

This repository contains reusable React components built with **shadcn/ui**, Tailwind CSS and TypeScript.

### Setup a Next.js project with shadcn

1. Create a new Next.js project with TypeScript:
   ```bash
   npx create-next-app@latest my-app -ts
   cd my-app
   ```
2. Install Tailwind CSS following the [Next.js guide](https://tailwindcss.com/docs/guides/nextjs).
3. Initialize shadcn/ui:
   ```bash
   npx shadcn-ui@latest init
   ```
4. Set the component path to `./components` (default is `components/ui`). If it doesn't exist, create it so that shared UI primitives can be colocated under `components/ui`.
5. Copy the contents of the `components` and `lib` folders from this repo into your project.
6. Install required dependencies:
   ```bash
   npm install lucide-react class-variance-authority @radix-ui/react-slot
   ```
7. Extend `tailwind.config.js` and `app/globals.css` with the snippets provided in this repository.

After setup you can import the `HeroSection` component from `@/components/blocks/hero-section` and use it in your pages.
