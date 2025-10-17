# Nuxt Chat App

## Setup

### Environment Variables

Create a `.env` file in the root directory with the following variables:

```bash
# OpenAI API Key (required for AI chat functionality)
NUXT_OPENAI_API_KEY=your_openai_api_key_here
```

To get an OpenAI API key:

1. Go to [OpenAI Platform](https://platform.openai.com/)
2. Sign up or log in to your account
3. Navigate to API Keys section
4. Create a new API key
5. Copy the key and paste it in your `.env` file

### Install Dependencies

Make sure to install dependencies:

```bash
# pnpm
pnpm install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# pnpm
pnpm dev
```

## Production

Build the application for production:

```bash
# pnpm
pnpm build
```

Locally preview production build:

```bash
# pnpm
pnpm preview
```
