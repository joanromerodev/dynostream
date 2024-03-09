# DynoStream

DynoStream is a video streaming application that allows you to enjoy a wide variety of multimedia content in one place. This repository contains the source code of the application, divided into two main folders: `back` for the backend and `front` for the frontend.

## Features

- Access to a wide library of movies, series, and documentaries.
- Intuitive and easy-to-use interface.
- Content categorization for a better browsing experience.
- Support for multiple devices, including desktop computers, tablets, and mobile devices.

## Clone and Run Locally

To clone and run the project locally, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/joanromerodev/dynostream.git
```

2. Install backend dependencies:

```bash
cd back
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open another terminal and navigate to the **front** folder

```bash
cd ../front
```

5. Update the local url in the front folder. Go and lookup for every axios request and update the current url with so that you can replicate **http://localhost:1818**

6. Start the Frontend app

```bash
npm run dev
```

## **IMPORTANT** Users Acess

There are 4 test users. I'll write their accounts, passwords and scopes.

1. User with all access - Premium Plan - (can see all categories and movies):

**Email:** jromero@dynostream.com
**Password** 12345

2. User with limited access - Standard Plan - (can see only some categories and movies):

**Email:** sking@dynostream.com
**Password** sking123

3. User with limited access - Basic Plan - (can see only one categories and some few movies):

**Email:** bgates@dynostream.com
**Password** bgates123

4. User with no access at all - Past Due Plan - (Can't access. Get automatically logged out):

**Email:** emusk@dynostream.com
**Password** emusk123

You're all set! You can now access the application locally from your browser by visiting **For backend: http://localhost:1818. For frontend: http://localhost:5173**

## Cloud Access

In addition to running the application locally, you can also access the cloud version of DynoStream through the following link: [DynoStream](https://dynostream.joanromerodev.com/).

Enjoy the streaming experience with DynoStream!
