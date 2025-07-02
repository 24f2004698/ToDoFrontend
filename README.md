Created with CodeSandbox

**ToDo Frontend**

A simple, user-friendly frontend application for managing your to-do tasks. This React-based project connects to a backend service to create, read, update, and delete tasks seamlessly.

---

## Features

* Create new to-do tasks
* View a list of existing tasks
* Mark tasks as completed or pending
* Edit task titles and descriptions
* Delete tasks you no longer need
* Responsive design for desktop and mobile

---

## Tech Stack

* **React** for building user interfaces
* **Axios** for HTTP requests
* **CSS / SCSS / Tailwind** (replace with your styling library)
* **React Router** for navigation (if applicable)

---

## Getting Started

Follow these steps to get the project running locally.

### Prerequisites

* Node.js (v14 or later)
* npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/24f2004698/ToDoFrontend.git
   cd ToDoFrontend
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

### Configuration

1. Create a `.env` file in the root directory.
2. Add the following variables (update the backend URL as needed):

   ```bash
   REACT_APP_API_URL=http://localhost:5000/api
   ```

### Running the App

```bash
npm start
# or
yarn start
```

This will start the development server at `http://localhost:3000`.

---

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Add a new task by entering a title and (optionally) a description, then click **Add Task**.
3. Click on a task to toggle its completion status.
4. Use the **Edit** button to update task details.
5. Click the **Delete** icon to remove a task.

---

## Project Structure

```
ToDoFrontend/
├── public/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Page-level components
│   ├── services/       # API call definitions
│   ├── App.js          # Main application component
│   ├── index.js        # Entry point
│   └── styles/         # Global and component-specific styles
├── .env
├── package.json
└── README.md
```

---

## Available Scripts

In the project directory, you can run:

* `npm start` or `yarn start` - Runs the app in development mode
* `npm run build` or `yarn build` - Builds the app for production
* `npm test` or `yarn test` - Runs tests (if configured)

---

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

Please make sure your code follows existing style conventions and includes relevant tests.
