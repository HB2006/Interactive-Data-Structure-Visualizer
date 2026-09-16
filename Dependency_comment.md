
// PACKAGE.JSON - WITH COMMENTS (Reference Only)


{
  "name": "my-nextjs-app",
  "version": "1.0.0",
  "description": "A modern Next.js application with TypeScript and Tailwind CSS",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "eslint . --ext .ts,.tsx",
    "type-check": "tsc --noEmit"
  },
  "dependencies": {
    // ===== CORE FRAMEWORK =====
    "react": "^18.2.0",                    // Core React library for building UI components with reusable, interactive elements
    "react-dom": "^18.2.0",                // Binds React components to the actual HTML DOM in the browser
    "next": "^15.0.0",                     // React framework providing server-side rendering, static generation, API routes, and performance optimization
    
    // ===== STYLING & DESIGN =====
    "tailwindcss": "^3.4.0",               // Utility-first CSS framework for rapidly building custom designs without writing CSS from scratch
    "tailwind-merge": "^2.2.0",            // Merges Tailwind CSS classes intelligently, resolving conflicts when combining multiple classes
    "class-variance-authority": "^0.7.0",  // Type-safe library for defining component styles with variants (different style states/variations)
    "clsx": "^2.1.0",                      // Utility for conditionally combining CSS class names together (conditional className generation)
    
    // ===== ICONS & ANIMATIONS =====
    "lucide-react": "^0.344.0",            // Beautiful, customizable SVG icon set available as React components
    "framer-motion": "^11.0.0",            // Animation library for creating smooth, performant animations and gesture interactions in React
    
    // ===== MARKDOWN & CONTENT =====
    "@mdx-js/react": "^3.0.0",             // Allows writing React components directly in Markdown files for interactive content
    "@next/mdx": "^15.0.0",                // Next.js plugin that integrates MDX support for rendering Markdown with embedded React components
    "react-markdown": "^9.0.0",            // React component that renders markdown content to HTML with support for custom components
    
    // ===== DATE & TIME =====
    "date-fns": "^3.0.0",                  // Modern JavaScript date utility library for parsing, formatting, and manipulating dates
    
    // ===== THEMES & STYLING =====
    "next-themes": "^0.2.0",               // Easy dark/light mode theme switching with persistence across page reloads
    
    // ===== FLOW & DIAGRAMS =====
    "@xyflow/react": "^12.0.0",            // Library for building interactive node-based editors, flowcharts, and diagrams (like Figma/Excalidraw)
    
    // ===== API DOCUMENTATION =====
    "next-swagger-doc": "^0.4.0"           // Next.js plugin to auto-generate Swagger/OpenAPI documentation from your API routes
  },
  "devDependencies": {
    // ===== TYPESCRIPT =====
    "typescript": "^5.3.0",                // Adds static type checking to JavaScript for catching errors at compile time
    "@types/react": "^18.2.0",             // TypeScript type definitions for React library
    "@types/react-dom": "^18.2.0",         // TypeScript type definitions for React DOM library
    "@types/node": "^20.0.0",              // TypeScript type definitions for Node.js runtime APIs and modules
    "@types/mdx": "^2.0.0",                // TypeScript type definitions for MDX files and components
    
    // ===== CODE QUALITY & LINTING =====
    "eslint": "^9.0.0",                    // Tool for identifying and fixing code style issues and bugs in JavaScript/TypeScript
    "eslint-config-next": "^15.0.0",       // Pre-configured ESLint rules optimized and recommended for Next.js projects
    "@eslint/eslintrc": "^3.0.0",          // Utilities for loading and validating ESLint configuration files
    
    // ===== CSS PROCESSING =====
    "postcss": "^8.4.0"                    // Tool for transforming CSS with JavaScript plugins (required and used internally by Tailwind CSS)
  }
}