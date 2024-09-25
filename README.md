## Usage

**fckMKBHD** currently offers a single variant: Node.js. You're welcome to contribute additional variants!

### Running with Node.js

1. Make sure Node.js is installed on your machine.
2. Execute `node fckmkbhd.js`.
3. Sit back and relax for a moment. 
4. All wallpapers will be saved in a newly created `downloads` subfolder. Cheers 🍻

### Logic

The code fetches a JSON file containing image URLs, processes each URL to download the corresponding images, and saves them in a `downloads` directory. It includes error handling for fetching the JSON and images, along with some delay between requests to avoid overwhelming the server.

**wallpapers are indeed hosted on an exposed CDN link, juiced them up in a json and dumped it into s3 bucket.**

### Tech Stack 

- JavaScript
- Amazon S3 bucket
- Node.js