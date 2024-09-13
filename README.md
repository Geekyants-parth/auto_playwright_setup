# auto_playwright_setup
This contains setup for auto playwright

Steps to start with auto playwright:
1. Installation: Begin by installing the auto-playwright dependency using npm:
`$ npm install auto-playwright -D`
2. Configuration: Auto Playwright leverages OpenAI’s capabilities. Export the API token as follows:
`$ export OPENAI_API_KEY=’sk-…”`
3. Usage: Import and use the auto function in your tests:
`import { test, expect } from “@playwright/test”;`
`import { auto } from “auto-playwright”;`