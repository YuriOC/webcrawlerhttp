# webcrawlerhttp
Project for HTTP course 

## Description
A web crawler built with JavaScript that maps website links and validates their HTTP responses.

## Features
- Crawls web pages and extracts all links
- Validates HTTP responses
- Normalizes URLs
- Tracks visited pages
- Reports broken links
- Generates a report of crawl results

## Installation
```bash
npm install
```

## Usage
To start crawling a website:
 ```bash
 npm start <baseURL>
 ```

Example:
```bash
npm start https://example.com
```

The crawler will:
1. Start from the base URL
2. Find all links on the page
3. Visit each valid link within the same domain
4. Generate a report showing all pages visited and any errors found

## Testing
```bash
npm test
```

## Technologies
- Node.js
- Jest (for testing)
- JavaScript modules

## Project Structure
- `crawl.js`: Main crawler logic
- `main.js`: Entry point
- `report.js`: Report generation
- `normalizeURL.js`: URL normalization utilities
- `getURLsFromHTML.js`: HTML parsing utilities
