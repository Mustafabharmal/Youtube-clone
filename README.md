# 📺 YouTube Clone Single Page Application

This project is a YouTube clone built using ReactJS, TailwindCSS, and RapidAPI as the data source. It includes features such as video cards, category filters, search functionality, related videos, video player, and responsive design.

## Features

- **Video Card**: Display videos with thumbnail and details.
- **Category Filters**: Filter videos by different categories.
- **Search Functionality**: Search for videos based on keywords.
- **Related Videos**: Show related videos based on the currently playing video.
- **Video Player**: Play videos within the application.
- **Responsive Design**: Optimized for various screen sizes.

## Tech Stack

- **ReactJS**: JavaScript library for building user interfaces.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **RapidAPI**: External data source providing video content.
- **React-router**: Library for handling routing within a React application.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Mustafabharmal/Youtube-clone.git
   cd Youtube-clone
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

   This will start the application on `http://localhost:3000`.

## Folder Structure

```
src/
|-- components/        # React components
|-- pages/             # Application pages
|-- services/          # API service functions
|-- App.css
|-- App.js             # Main application component
|-- index.css
|-- index.js           # Entry point
```

## Deployment

To deploy the application, build the project and deploy the generated `dist` folder to a hosting service:

```bash
npm run build
```

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
