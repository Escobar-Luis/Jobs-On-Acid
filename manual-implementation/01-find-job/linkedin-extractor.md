# LinkedIn Job Content Extraction

## Method 1: Manual Copy-Paste (Recommended)
1. Open LinkedIn job posting
2. Select all text content (Cmd/Ctrl+A)
3. Copy and paste into job parser prompt
4. Remove navigation/sidebar content manually

## Method 2: Browser Developer Tools
1. Right-click on job posting content
2. Inspect Element
3. Find main job content container
4. Copy outerHTML or innerText
5. Feed to parser prompt

## Method 3: Simple Web Scraping (Future automation)
- Use Playwright/Puppeteer to extract job content
- Target specific LinkedIn job posting selectors
- Clean HTML before feeding to parser 