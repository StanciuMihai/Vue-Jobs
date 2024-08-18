# Job Posting Management System

This Vue.js-based application is designed for managing job listings, catering to both job seekers and employers. The project includes a range of components and features that allow users to add, edit, view, and delete job postings seamlessly.
Key Features:

  -  Add Job Postings: A form-driven interface for employers to create job listings, including details like job type, title, description, salary, location, and company information.
  -  Edit Job Postings: An intuitive editing interface that allows employers to update existing job listings with real-time data fetching and pre-population of fields.
  -  View Job Details: Detailed job descriptions, including company information, are presented in a clean, user-friendly layout.
  -  Delete Job Postings: A secure deletion process for employers, with confirmation prompts to prevent accidental data loss.
  -  Dynamic Forms: Reactive form handling with real-time validation and feedback via Vue's reactivity system.
  -  User Notifications: Toast notifications to inform users of the success or failure of their actions, ensuring a smooth user experience.
  -  Responsive Design: Mobile-first design approach, ensuring compatibility across various devices and screen sizes.
  -  Component Reusability: Modular components such as forms, cards, and layout sections, designed for easy reuse and customization.
  -  Navigation and Routing: Seamless navigation with Vue Router, allowing users to move between pages like job listings, add/edit forms, and detail views without reloading the page.

## Technologies Used:

  -  Vue.js: A progressive JavaScript framework for building user interfaces.
  -  Vue Router: For managing navigation between views and pages.
  -  Vue Toastification: For displaying non-blocking notifications.
  -  Axios: For making HTTP requests to backend APIs.
  -  Tailwind CSS: For styling components with utility-first CSS classes.

This project can be an excellent starting point for building more complex job board applications or integrating with backend services for a complete job management system.

![alt text](https://raw.githubusercontent.com/StanciuMihai/Vue-Jobs/main/src/assets/preview1.PNG)
![alt text](https://raw.githubusercontent.com/StanciuMihai/Vue-Jobs/main/src/assets/preview2.PNG)
![alt text](https://raw.githubusercontent.com/StanciuMihai/Vue-Jobs/main/src/assets/preview3.PNG)


## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### In order for the app to function properly JSON server must be started first

```sh
npm run server
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
