# AI Chatbot

An Open-Source AI Chatbot Template Built With Next.js and AI SDK.

## Features

- [Next.js](https://nextjs.org) App Router
  - Advanced routing for seamless navigation and performance
  - React Server Components (RSCs) and Server Actions for server-side rendering and increased performance
- AI SDK
  - Unified API for generating text, structured objects, and tool calls with LLMs
  - Hooks for building dynamic chat and generative user interfaces
  - Supports multiple model providers
- [shadcn/ui](https://ui.shadcn.com)
  - Styling with [Tailwind CSS](https://tailwindcss.com)
  - Component primitives from [Radix UI](https://radix-ui.com) for accessibility and flexibility
- Data Persistence
  - PostgreSQL database for saving chat history and user data
  - Blob storage for efficient file storage
- [NextAuth.js](https://github.com/nextauthjs/next-auth)
  - Simple and secure authentication

## Model Providers

This template supports multiple LLM providers that you can configure with just a few lines of code.

## Running locally

You will need to set up the following environment variables in a `.env` file:

```env
# Database
POSTGRES_URL=your_postgres_connection_string

# Auth
AUTH_SECRET=your_auth_secret_key

# AI Provider credentials
# Add your chosen AI provider credentials here
```

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various AI and authentication provider accounts.

To run the application:

```bash
pnpm install
pnpm dev
```

Your app should now be running on [localhost:3000](http://localhost:3000/).
