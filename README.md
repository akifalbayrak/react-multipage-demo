# React Router App

This repository contains a React application utilizing `react-router-dom` for managing routing within the app. The app is structured into different pages and components for handling various functionalities.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/react-router-app.git
   ```

2. Install dependencies:
   ```bash
   cd react-router-app
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## Structure

The application is structured as follows:

- **RootLayout:** The main layout component serving as the base layout for other pages.
- **Pages:**
  - **Home:** The landing page of the application.
  - **Events:**
    - **EventsRootLayout:** Layout specific to event-related pages.
    - **EventsPage:** Displaying a list of events.
    - **EventDetailPage:** Details of a specific event, including options to edit or delete.
    - **EditEventPage:** Form for editing an event.
    - **NewEventPage:** Form for creating a new event.
  - **NewsletterPage:** Page for managing newsletters.

## Routes Configuration

The app's routing is configured using `createBrowserRouter` from `react-router-dom`. Here's a brief overview of the configured routes:

- `/`: Root path displaying the `RootLayout` with the `HomePage` as the default index.
- `/events`:
  - `EventsRootLayout` serving as the layout for event-related pages.
  - `EventsPage` listing all events.
  - `EventDetailPage` showing details of a specific event, with options for deletion and editing.
  - `EditEventPage` for modifying event details.
  - `NewEventPage` for creating a new event.
- `/newsletter`: Page for managing newsletters.

The routes are configured to render specific components based on the URL path and provide different functionalities accordingly.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

---
![image](https://github.com/akifalbayrak/react-multipage/assets/142679378/1c8abdeb-4a3c-493f-8720-6f3e9f6a6abe)
![image](https://github.com/akifalbayrak/react-multipage/assets/142679378/c953114f-7201-4241-a613-788b10980a12)
![image](https://github.com/akifalbayrak/react-multipage/assets/142679378/e62109ee-7d1d-4fe8-904c-563fa0144ab9)

