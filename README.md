# Web Crawler in JavaScript

A simple, lightweight web crawler built with JavaScript using [`jsdom`](https://github.com/jsdom/jsdom) for HTML parsing and [`jest`](https://jestjs.io/) for testing.

## Features

- Crawl and extract all links from a given URL
- Normalize URLs to avoid redundant crawling
- Depth-limited crawling to prevent infinite loops
- Unit tests to ensure correctness and reliability

## Tech Stack

- **Node.js** – JavaScript runtime
- **jsdom** – For parsing and manipulating HTML documents
- **jest** – For writing and running tests

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- npm

### Installation

1. Clone the repository:

```bash
git clone https://github.com/tianyachen/webcrawlerhttp.git
cd webcrawlerhttp
```

2. Install dependencies:

```bash
npm install
```

### Running the Crawler

```bash
node start [https://example.com]
```

#### Example Output

```text
starting crawl of https://example.com
actively crawling : https://example.com
===========
REPORT
===========
Found 1 links to page: example.com
===========
END REPORT
===========
```

### Running Tests

```bash
npm test
```
