React-query – OPEN-SOURCE

https://github.com/tannerlinsley/react-query
https://react-query-v2.tanstack.com/

Overview
React Query is often described as the missing data-fetching library for React, but in more technical terms, it makes fetching, caching, synchronizing and updating server state in your React applications a breeze.

Motivation
Out of the box, React applications do not come with an opinionated way of fetching or updating data from your components so developers end up building their own ways of fetching data. This usually means cobbling together component-based state and effect using React hooks, or using more general purpose state management libraries to store and provide asynchronous data throughout their apps.

While most traditional state management libraries are great for working with client state, they are not so great at working with async or server state. This is because server state is totally different. For starters, server state:

•	Is persisted remotely in a location you do not control or own
•	Requires asynchronous APIs for fetching and updating
•	Implies shared ownership and can be changed by other people without your knowledge
•	Can potentially become "out of date" in your applications if you're not careful
Once you grasp the nature of server state in your application, even more challenges will arise as you go, for example:

•	Caching... (possibly the hardest thing to do in programming)
•	Deduping multiple requests for the same data into a single request
•	Updating out of date data in the background
•	Knowing when data is "out of date"
•	Reflecting updates to data as quickly as possible
•	Performance optimizations like pagination and lazy loading data
•	Managing memory and garbage collection of server state
•	Memoizing query results with structural sharing
If you're not overwhelmed by that list, then that must mean that you've probably solved all of your server state problems already and deserve an award. However, if you are like a vast majority of people, you either have yet to tackle all or most of these challenges and we're only scratching the surface!

React Query is hands down one of the best libraries for managing server state. It works amazingly well out-of-the-box, with zero-config, and can be customized to your liking as your application grows.

React Query allows you to defeat and overcome the tricky challenges and hurdles of server state and control your app data before it starts to control you.

On a more technical note, React Query will likely:

•	Help you remove many lines of complicated and misunderstood code from your application and replace with just a handful of lines of React Query logic.
•	Make your application more maintainable and easier to build new features without worrying about wiring up new server state data sources
•	Have a direct impact on your end-users by making your application feel faster and more responsive than ever before.
•	Potentially help you save on bandwidth and increase memory performance

Formik - OPEN-SOURCE

https://github.com/formium/formik
https://formik.org/

Overview
Let's face it, forms are really verbose in React. To make matters worse, most form helpers do wayyyy too much magic and often have a significant performance cost associated with them. Formik is a small library that helps you with the 3 most annoying parts:

•	Getting values in and out of form state
•	Validation and error messages
•	Handling form submission

By colocating all of the above in one place, Formik will keep things organized--making testing, refactoring, and reasoning about your forms a breeze.

React-Spring – OPEN-SOURCE

https://github.com/pmndrs/react-spring
https://react-spring.io/

Overview
react-spring is a spring-physics based animation library that should cover most of your UI related animation needs. It gives you tools flexible enough to confidently cast your ideas into moving interfaces.

This library represents a modern approach to animation. It is very much inspired by Christopher Chedeau's animated and Cheng Lou's react-motion. It inherits animated's powerful interpolations and performance, as well as react-motion's ease of use. But while animated is mostly imperative and react-motion mostly declarative, react-spring bridges both. You will be surprised how easy static data is cast into motion with small, explicit utility functions that don't necessarily affect how you form your views.


Yup – OPEN-SOURCE

https://github.com/jquense/yup

Overview
Yup is a JavaScript schema builder for value parsing and validation. Define a schema, transform a value to match, validate the shape of an existing value, or both. Yup schema are extremely expressive and allow modeling complex, interdependent validations, or value transformations.

Yup's API is heavily inspired by Joi, but leaner and built with client-side validation as its primary use-case. Yup separates the parsing and validating functions into separate steps. cast() transforms data while validate checks that the input is the correct shape. Each can be performed together (such as HTML form validation) or seperately (such as deserializing trusted data from APIs).

TailwindCSS – OPEN-SOURCE

https://github.com/tailwindlabs/tailwindcss
https://tailwindcss.com/

Overview
A utility-first CSS framework for rapidly building custom user interfaces.

Storybook – OPEN-SOURCE

https://github.com/storybookjs/storybook/
https://storybook.js.org/

Overview
Storybook is a tool for UI development. It makes development faster and easier by isolating components. This allows you to work on one component at a time. You can develop entire UIs without needing to start up a complex dev stack, force certain data into your database, or navigate around your application.

Storybook helps you document components for reuse and automatically visually test your components to prevent bugs. Extend Storybook with an ecosystem of addons that help you do things like fine-tune responsive layouts or verify accessibility.

Storybook integrates with most popular JavaScript UI frameworks and (experimentally) supports server-rendered component frameworks such as Ruby on Rails.

NextJS – OPEN-SOURCE

https://github.com/vercel/next.js
https://nextjs.org/

Overview
To build a complete web application with React from scratch, there are many important details you need to consider:

•	Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.
•	You need to do production optimizations such as code splitting.
•	You might want to statically pre-render some pages for performance and SEO. You might also want to use server-side rendering or client-side rendering.
•	You might have to write some server-side code to connect your React app to your data store.
A framework can solve these problems. But such a framework must have the right level of abstraction — otherwise it won’t be very useful. It also needs to have great "Developer Experience", ensuring you and your team have an amazing experience while writing code.

Next.js: The React Framework
Enter Next.js, the React Framework. Next.js provides a solution to all of the above problems. But more importantly, it puts you and your team in the pit of success when building React applications.

Next.js aims to have best-in-class developer experience and many built-in features, such as:

•	An intuitive page-based routing system (with support for dynamic routes)
•	Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis
•	Automatic code splitting for faster page loads
•	Client-side routing with optimized prefetching
•	Built-in CSS and Sass support, and support for any CSS-in-JS library
•	Development environment with Fast Refresh support
•	API routes to build API endpoints with Serverless Functions
•	Fully extendable
Next.js is used in tens of thousands of production-facing websites and web applications, including many of the world's largest brands.
