# :wave: Welcome to GoldenBook

## Overview

The Golden Book application focuses on providing a curated experience for guests staying in 4 and 5-star hotels in Portugal. The application showcases a collection of photographs and articles highlighting the city's most culturally significant landmarks, reviews of boutique stores, luxury brands, restaurants, and other businesses. The primary goal is to offer users a comprehensive guide with geolocation maps, up-to-date recommendations, personalized advertisements, and suggestions. Future enhancements may include features such as reservation capabilities, discount coupons, and more.

## Documentation Structure

### [Introduction](README.md)

Welcome to the Golden Book project! In this section, you'll find a brief overview of the project's goals and its significance in enhancing the experience for hotel guests in Portugal.

## :sparkles: Quick links

### :bank: [Architecture](#architecture) 

### :art: [Images and Diagrams](#images-and-diagrams)

### :running: [How to Run the Project](#how-to-run-the-project)

The architecture of the Golden Book project is designed for professionalism and scalability. Here are the key technological choices made:

#### Mobile Framework

We've chosen to leverage Ionic with Angular for the mobile framework. This combination provides a powerful and flexible solution for cross-platform mobile applications, ensuring a seamless user experience across different devices.

#### Backend with Nest.js

The backend architecture is built on Nest.js, a progressive Node.js framework. Nest.js provides a robust foundation for building scalable and maintainable server-side applications. It enables efficient handling of data, ensuring a smooth communication flow between the mobile app and the server.

#### Firebase

Firebase is integrated into the project for its capabilities in handling real-time data synchronization, authentication, and hosting. This ensures that users receive updated recommendations and personalized content promptly.


## Individual Sections

### Architecture

In this section, we delve into the overall architecture of the Golden Book project.

#### Mobile Framework

The mobile application is developed using Ionic in conjunction with Angular. Ionic offers a comprehensive framework for building cross-platform mobile applications, and when paired with Angular, it allows for the creation of a seamless and responsive user interface. This combination ensures that the Golden Book app delivers a consistent and enjoyable user experience across various devices and platforms.

#### Backend with Nest.js

The backend of the Golden Book project is powered by Nest.js, a progressive Node.js framework. Nest.js provides a solid foundation for constructing scalable and maintainable server-side applications. Leveraging TypeScript, Nest.js offers a well-organized code structure and robust features such as dependency injection, middleware support, and efficient handling of HTTP requests. The decision to use Nest.js reflects our commitment to building a backend system that is not only performant but also easy to extend and manage as the project grows.

#### Firebase

Firebase plays a crucial role in the Golden Book project, providing essential functionalities for real-time data synchronization, user authentication, and hosting. The integration of Firebase ensures that the content displayed in the app is always up-to-date, as changes made on the server side are immediately reflected on the user's device. Firebase Authentication enhances the app's security, allowing users to create accounts and securely access personalized content. Additionally, Firebase Hosting enables seamless deployment and hosting of the Golden Book app, contributing to a reliable and efficient user experience.


## Images and Diagrams

Comming soon...


## How to Run the Project

Below are the steps to run both the frontend and backend of the Golden Book project in your development environment.

### Frontend (Ionic with Angular)

1. Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

2. Navigate to the frontend project directory:

    ```bash
    cd path/to/your/golden-book/frontend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Serve the application:

    ```bash
    ionic serve
    ```

   This will start the development server, and you can view the application in your browser at http://localhost:8100/.

5. Build the application:

    ```bash
    ionic build
    ```

   This command will generate the production-ready build in the `www` directory.

### Backend (Nest.js)

1. Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

2. Navigate to the backend project directory:

    ```bash
    cd path/to/your/golden-book/backend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the server:

    ```bash
    npm run start
    ```

   The server will be available at http://localhost:3000/ by default.

5. Build the application:

    ```bash
    npm run build
    ```

   This command will compile the TypeScript code into JavaScript in the `dist` directory.

Now, you should have both the frontend and backend of the GoldenBook project running in your development environment. Happy coding!
