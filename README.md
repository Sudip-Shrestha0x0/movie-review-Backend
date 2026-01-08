# Movie Review Site - Backend (Render)

This is the backend for our movie review site, built with Strapi CMS.

## Type of Review Site
Movie Reviews

## Headless CMS Choice
Strapi

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run develop
```

3. The admin panel will be available at http://localhost:1337/admin
4. The API will be available at http://localhost:1337/api

## API Endpoints

- GET /api/reviews - Get all reviews
- GET /api/reviews/:id - Get a single review

## Content Structure

The Review content type includes:
- Title (text)
- Description (long text)
- Rating (decimal)
- Director (text)
- Release Year (integer)
- Genre (text)
- Image URL (text)
- Full Review (rich text)

## Technologies Used

- Strapi
- Postgres database
- Node.js

-Render (for BackEnd Or you can use railway.app for backend)
