# Wiki Search App

A simple Next.js application that allows users to search for Wikipedia articles and view their summaries. The app fetches data from the Wikipedia API and displays the results in a clean and responsive UI.

## Features

- Search for Wikipedia articles by entering a search term.
- View article summaries, titles, and thumbnails (if available).
- Responsive design for optimal viewing on different devices.
- Error handling and loading states for a better user experience.

## Technologies Used

- **Next.js**: A React framework for server-side rendering and static site generation.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Wikipedia API**: Used to fetch search results and article details.

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository:**

   ```bash
      git clone https://github.com/your-username/wiki-search-app.git
       cd wiki-search-app
2. **Install dependencies:**

    ```bash

      npm install
      # or
      yarn install

3. **Run the development server:**

    ```bash

       npm run dev
       # or
       yarn dev

4. **Open your browser and navigate to http://localhost:3000.**

## Project Structure
   
* app/: Contains the main application pages and components.

  - page.jsx: The main search page.

  - error.jsx: Error boundary component for handling errors.

  - loading.jsx: Loading state component.

* components/: Reusable components like Item and NavBar.

* lib/: Utility functions like getWikiResult for fetching data.

* public/: Static assets like images and fonts.

* styles/: Global styles and Tailwind configuration.

## Environment Variables

 No environment variables are required for this project as it directly accesses the Wikipedia API.



## Contributing

 Contributions are welcome! If you find any issues or want to add new features, feel free to open a pull request.

 1. Fork the repository.

 2. Create a new branch (git checkout -b feature/YourFeatureName).

 3. Commit your changes (git commit -m 'Add some feature').

 4. Push to the branch (git push origin feature/YourFeatureName).

 5. Open a pull request.

