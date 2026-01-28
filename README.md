# 100Jobs - React Job Board
A modern job board web application built with React and Vite as a comprehensive learning project to master React fundamentals, component architecture, and modern frontend development practices. The application features full CRUD functionality for job listings with a beautiful, responsive interface.

![100Jobs Homepage](public/screenshots/homepage.png)

Link to project: https://100jobs.netlify.app/ (Frontend only) | Local Development: http://localhost:3000 (Full CRUD with JSON Server)

## How It's Made:
**Tech used:** React, Vite, JavaScript, Tailwind CSS, React Router, JSON Server, React Icons, React Toastify

This application was built as a complete React-based single-page application demonstrating modern frontend development practices. The project started as a React learning exercise and was transformed into a personalized "100Jobs" platform with custom branding, professional styling, and comprehensive job management functionality.

The application uses React 18 with functional components and modern hooks for state management. Navigation is handled through React Router with programmatic routing and clean URL management. The component architecture follows React best practices with proper separation between reusable UI components, page-level components, and layout components.

Tailwind CSS provides utility-first styling with a custom light blue theme and professional "100Jobs" branding. The design is completely mobile-first and scales beautifully across all devices. JSON Server provides a full REST API simulation for CRUD operations during local development.

State management demonstrates React patterns including lifting state up and local component state for form handling. All API interactions use modern fetch() with async/await patterns for clean, readable asynchronous code.

## Optimizations
Implemented proper React optimization techniques including key props for list rendering, conditional rendering for loading states, and efficient state updates. Used React Router for potential code splitting and lazy loading opportunities.

Vite's build process automatically optimizes bundle size through tree shaking and code splitting. Tailwind CSS purges unused styles in production builds, significantly reducing CSS bundle size. Configured Vite proxy for seamless API communication during development.

Optimized the responsive design using Tailwind's mobile-first approach with CSS Grid and Flexbox implementations. Touch targets are properly sized for mobile interaction, and navigation adapts seamlessly between desktop and mobile viewports.

## Lessons Learned:
**React Architecture** - This project provided hands-on experience with core React concepts including component composition, props vs. state, and lifecycle methods through hooks. Understanding how data flows through components and when to lift state up was crucial for building maintainable applications.

**Modern Development Tools** - Working with Vite demonstrated the importance of modern build tools and how they improve developer experience through fast builds, HMR, and optimized production bundles. The difference between Vite and older tools highlighted how tooling choices impact development velocity.

**API Integration** - Implementing full CRUD operations with JSON Server taught important lessons about REST API design, asynchronous JavaScript, and error handling. Understanding how frontend state management integrates with backend data persistence was crucial for building complete applications.

**Project Transformation** - Converting an existing React project into a personalized application taught valuable lessons about codebase exploration, systematic refactoring, and maintaining functionality while implementing design changes. This mirrors real-world scenarios where existing applications need rebranding or feature modifications.

## Future Improvements
Add user accounts so people can save their favorite job listings. Include basic search functionality to filter jobs by title or company name.

Implement job categories to organize listings better. Add the ability to mark jobs as "applied" with application dates. Include a simple form for employers to submit new job postings.

## Examples of Other Work
- **[Portfolio Website](https://github.com/JackGer26/portfolio)** - Modern React portfolio showcasing technical projects and skills
- **[Binary Upload Boom](https://github.com/JackGer26/binary-upload-boom)** - Full-stack social media application with Node.js and MongoDB
- **[Green Cars Airport Transfers](https://github.com/JackGer26/Green-Cars-Airport-Transfers)** - Professional freelance business website with Email.js integration