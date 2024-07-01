<div align="center">
  <br />
  
  <h3 align="center">Talea: A Video Chat Application</h3>
</div>

## Table of Contents

1. [Introduction](#introduction)
2. [Demo](#demo)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)

## Introduction

Talea, built with Next.js and TypeScript, is a video chat application. It allows secure user login, meeting creation, and management of meetings, including features such as recording, screen sharing, and participant control.

## Demo

Here is the Talea working:
![](https://github.com/pylhr/talea/blob/master/public/demo-talea.gif)


## Tech Stack

- Next.js
- TypeScript
- Clerk (for authentication)
- Stream-io (for real-time functionalities)
- Tailwind CSS

## Features

- **Authentication**: Secure user login using Clerk, supporting social sign-on and email/password methods.
- **Meeting Management**: Create, join, and manage meetings with features like recording, screen sharing, and participant control.
- **Scheduled Meetings**: Schedule future meetings with details accessible on the platform.
- **Meeting History**: Access past meetings and their recordings for review.
- **Responsive Design**: Optimized for various screen sizes and devices.

## Quick Start

Follow these steps to set up the project locally on your machine:

**Prerequisites**

Ensure you have Git, Node.js, and npm installed on your machine.

**Cloning the Repository**

```bash
gh repo clone pylhr/talea
cd talea
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named .env in the root of your project and add the following content:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk & getstream credentials. You can obtain these credentials by signing up on the Clerk website and getstream website

**Running the Project**

npm run dev
Open http://localhost:3000 in your browser to view the project.

