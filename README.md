# TwittSave - Twitter (X) Video Downloader API (SOON🎉)

**TwittSave** is a powerful and easy-to-use Twitter (X) video downloader that allows users to download videos directly from **[TwittSave](https://twittsave.com/)**.

## Features

*   Download Twitter (X) videos in high quality
*   Supports various video resolutions
*   No need to install software or extensions
*   Works on mobile and desktop browsers
*   Fast and secure processing

## Installation

If you want to run the script locally, follow these steps:

1.  Clone the repository:
    
    ```bash
    git clone https://github.com/ISMAILEA12/twittsave.git
    cd twittsave
    ```
    
2.  Install dependencies:
    
    ```bash
    npm install
    ```
    
3.  Run the script:
    
    ```bash
    node index.js
    ```
    
4.  Open your browser and navigate to:
    
    ```
    http://localhost:3000
    ```
    

## Usage

1.  Enter the Twitter (X) video URL in the input field.
2.  Click the **Download** button.
3.  The system processes the request and provides a direct download link.

## API Endpoints

*   **Download Twitter (X) Video**
    
    ```http
    GET /api/download?url={video_url}
    ```
    
    *   **Parameters:** `url` (Twitter video link)
    *   **Response:** JSON with download link

## Technologies Used

*   Node.js
*   Express.js
*   Cheerio (for parsing Twitter pages)
*   Axios (for fetching video data)

## Upcoming Features

*   Announcement system for latest updates
*   More video resolution options

## Contributing

We welcome contributions! To contribute:

1.  Fork the repository.
2.  Create a new branch.
3.  Make your changes.
4.  Submit a pull request.

## License

This project is licensed under the **MIT License**.

## Contact

For any issues or inquiries, open an issue on [GitHub](https://github.com/yourusername/twittsave) or contact us at **[support@twittsave.com](mailto:support@twittsave.com)**.
