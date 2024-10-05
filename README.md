# Gogolplex

**Gogolplex** is a simplified search engine created as part of a scientific and technical project. This engine crawls web pages, indexes them, and enables fast search using the **TF-IDF** algorithm to rank results by relevance. The project focuses primarily on technical aspects such as crawling, indexing, and searching.

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributors](#contributors)
7. [License](#license)

## Features
- **Crawler**: Automatically explores web pages while respecting `robots.txt` rules.
- **Indexing**: Creates an inverted index to optimize searches.
- **Keyword Search**: Uses the **TF-IDF** algorithm to rank results by relevance.
- **Simple User Interface**: A web interface for users to perform keyword searches.
- **Performance Optimization**: Capable of handling requests quickly and efficiently.

## Technologies Used
- **Language**: Python
- **Libraries**:
  - Flask (for the web interface)
  - Scrapy (for the crawler)
  - Whoosh (for indexing and searching)
  - BeautifulSoup (for web page scraping)
- **Database**: SQLite
- **Frontend**: HTML, CSS, JavaScript

## Installation

### Prerequisites
- Python 3.8+
- Git installed on your machine

### Installation Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Emhu_19/gogolplex.git
   cd gogolplex
