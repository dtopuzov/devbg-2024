# Demos for DevBG event

Demos for [Past, present and future of Web Testing](https://dev.bg/event/qa-past-present-and-future-of-web-testing/) event.

## Getting Ready

Install dependencies:

```bash
npm ci
```

In addition that that if you also want to run Playwright tests you need to install Playwright dependencies/browsers via:

```bash
npx playwright install
```

## Development

Starting the app:

```bash
npm run dev
```

...and happy codding!

## Testing

Run jsdom based tests (watch mode by default):

```bash
npm run test
```

Run Playwright based components tests (no watch by default):

```bash
npm run test:playwright
```
