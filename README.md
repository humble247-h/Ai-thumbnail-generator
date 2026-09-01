# AI Thumbnail Generator

An AI-powered tool that generates YouTube thumbnails and titles using OpenAI's API.

## Features

- Generate optimized YouTube thumbnails using AI
- Create compelling video titles
- Powered by OpenAI GPT models

## Setup

### Prerequisites

- Python 3.9+
- OpenAI API key
- Vercel account (for deployment)

### Installation

1. Clone the repository
2. Set your OpenAI API key as an environment variable:
   ```bash
   export OPENAI_API_KEY=your_key_here
   ```
3. Deploy to Vercel or run locally

## Usage

Send a GET request to the API endpoint with your topic:

```bash
curl "https://your-domain.vercel.app/api/api?topic=Your+Topic"
```

## Deployment

Deployed on Vercel. Connect this repository to Vercel for automatic deployments.

## Environment Variables

- `OPENAI_API_KEY`: Your OpenAI API key

## License

MIT
