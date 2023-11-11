# JS Sniper

![JS Sniper Logo](main/Screenshot_2.png)

**JS Sniper** is a Python script designed to extract information from JavaScript files obtained from either a single URL or a list of URLs provided in a text file.

## Features

- Asynchronous processing of URLs for efficient extraction.
- Detection of various sensitive information, including API keys, access tokens, and more.
- Support for both single URL input and batch processing from a file containing multiple URLs.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Examples](#examples)
- [Recommendations](#recommendations)
- [Contact](#Contact)

## Getting Started

### Prerequisites

Ensure you have the following prerequisites installed before running JS Sniper:

- **Python 3.x:** Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

- **Dependencies:** Install the required dependencies using the following commands:

    ```bash
    pip install aiohttp colorama
    pip install request
    pip install aiohttp
    pip install asyncio
    ```

    These commands install the necessary libraries for asynchronous HTTP requests (`aiohttp`), colored terminal output (`colorama`), handling HTTP requests (`request`), and asynchronous programming (`asyncio`).

### Installation

No specific installation is required. Simply clone or download the script and ensure you have the prerequisites installed.

## Usage

1. Run the script:

    ```bash
    python js_sniper.py
    ```

2. Choose an option:
    - Enter a single URL.
    - Enter a file path containing multiple URLs.

### Examples

#### Single URL

```bash
python js_sniper.py
# Enter the URL: [Your URL]
```

### Recommendations
If errors occur during processing, review and check the affected URLs manually.
No sensitive information identified in the processed URLs if no valid pages.

### Contact
Please if you have any questions or comments feel free to contact me, 
Twitter @PerhapsMalek
Linkedin @MalekAlthubiany


