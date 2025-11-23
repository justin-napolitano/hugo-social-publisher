# Hugo Social Publisher

Hugo Social Publisher is an experimental project aiming to automate the posting of Hugo blog content to various social media platforms using Python. It explores a workflow where metadata files within Hugo posts are parsed to generate social media posts programmatically.

## Features

- Parses YAML configuration files embedded in Hugo blog posts to determine social media publishing targets.
- Generates post content and metadata for social APIs like Mastodon, LinkedIn, and others.
- Prototype Python scripts to automate social posting based on post metadata.

## Tech Stack

- Hugo (static site generator) for blog content
- Python for automation and API interactions
- YAML for post-level publish configuration

## Getting Started

### Prerequisites

- Python 3.x installed
- Access to social media API credentials (not included)

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/hugo-social-publisher.git
cd hugo-social-publisher
```

Install Python dependencies (assumed, as none specified):

```bash
pip install -r requirements.txt
```

*Note: requirements.txt is not present; add dependencies as needed.*

### Running

The repository currently contains prototype code and markdown notes. To build your own automation:

1. Add a `publish.yaml` file to your Hugo post directories specifying which social platforms to publish to.
2. Use or develop a Python script to parse these YAML files and generate API calls.

## Project Structure

```
/images          # Images used in documentation and mockups
index.md         # Project notes and design thoughts
readme.md        # This README file
```

## Future Work / Roadmap

- Develop a robust Python application to parse Hugo posts and publish to social media APIs.
- Support more social platforms with configurable options.
- Automate retrieval of Open Graph metadata from rendered HTML.
- Improve error handling and scheduling capabilities.
- Document API requirements and authentication flows.

---

*This project is in an early conceptual phase and serves as a personal experiment.*