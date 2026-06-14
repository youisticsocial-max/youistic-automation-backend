# Youistic Automation Backend

Node.js / Express backend service for automated white-label website generation and deployment.

## Features
- Dynamic token substitution for 12 distinct business templates.
- Automated zip packaging and publishing via Netlify API.
- Native CORS and OPTIONS preflight handlers enabled.

## local Installation & Running
1. Install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env` file in the root directory:
   ```env
   NETLIFY_TOKEN=your_netlify_token_here
   GITHUB_TOKEN=your_github_token_here
   ```
3. Start the server:
   ```bash
   npm start
   ```

## Render.com Deployment Steps
See the detailed step-by-step instructions in the chat or deployment documentation to launch this service on Render.
