# Portfolio Templates

This repository contains a collection of modern, responsive, and customizable portfolio templates built with Next.js and Tailwind CSS. It is designed to be used as a starting point for building professional portfolios for various professions, such as gym trainers, photographers, and more.

## Current Template

- **Gym Trainer Portfolio** 
  - Features a strong aesthetic suitable for fitness professionals.
  - Showcases a hero section, an interlocking masonry featured gallery, and a philosophy section.

## Getting Started

To use this template, clone the repository and run the development server:

```bash
git clone git@github.com:ASHISHSINGHNEGI/portfolio_templates.git
cd portfolio_templates
npm install
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Customization

You can start editing the template by modifying the components in the `app/components` directory and the main page at `app/page.tsx`.
- Images are stored in the `public/asset` folder.
- Update `app/components/FeaturedGallery.tsx` to add your own gallery images.
- Modify `app/components/PhilosophySection.tsx` and `app/components/HeroSection.tsx` to update the text content.

## Technologies Used

- [Next.js](https://nextjs.org) (App Router)
- [Tailwind CSS](https://tailwindcss.com)
- [Lucide React](https://lucide.dev) (for icons)
