# PexelsHub

PexelsHub is a web application built with Next.js that integrates with the Pexels API to provide curated collections of high-quality images. This app allows users to explore and search for beautiful and free stock photos.

## Features

- **Search functionality**: Search for images based on keywords or categories.
- **Curated Collections**: Explore handpicked image collections.
- **Responsive design**: The app is fully responsive and works seamlessly across devices.
- **Next.js API routes**: Uses Next.js API routes to fetch data from the Pexels API.

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **API**: Next.js API Routes
- **Images**: Pexels API
- **State Management**: React hooks and Context API

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SARVESHYOGI/pexelshub.git
    ```

2. Install the required dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file at the root of the project and add your Pexels API key:
    ```bash
    PEXELS_API_KEY=your-pexels-api-key
    ```

4. Start the development server:
    ```bash
    npm run dev
    ```

    The app will be running on `http://localhost:3000`.

## How It Works

- The frontend of the application is built using Next.js and React. It fetches high-quality images from the Pexels API through API routes.
- The `/api/images` route in the Next.js app handles requests to the Pexels API and returns image data to the frontend.
- Users can search for images and view curated collections directly from the home page.

## Environment Variables

- `PEXELS_API_KEY`: Your Pexels API key. You can obtain this key from [Pexels API](https://www.pexels.com/api/).


## **Screenshots**

Example:  
![Screenshot of website](./src/images/s1.png)
![Screenshot of website](./src/images/s2.png)
![Screenshot of website](./src/images/s3.png)


## Contributing

Feel free to fork the repository and submit pull requests with any improvements or fixes!


## Acknowledgements

- [Pexels API](https://www.pexels.com/api/) for providing beautiful, free stock images.
- [Next.js](https://nextjs.org/) for the framework.
- [Tailwind CSS](https://tailwindcss.com/) for styling.
