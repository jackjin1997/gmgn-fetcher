# gmgn-scraper
scrape data from gmgn.ai

## Development
- Node.js >= v18.20.3
- Chrome browser installed

## Installation
```bash
# Install dependencies
pnpm install

# Install Chrome for Puppeteer
npx puppeteer browsers install chrome
```

## Environment Variables
Sign up for a captcha api key from [2captcha](https://2captcha.com/)
```bash
# Create a .env file
touch .env

# Add your API key
CAPTCHA_API_KEY=your_api_key
```

## Usage
```bash
pnpm start
```
