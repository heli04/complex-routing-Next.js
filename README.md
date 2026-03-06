# Next.js Blog Demo Application

A modern blog application built with Next.js 13+ (App Router), showcasing advanced routing techniques and a clean, user-friendly interface.

## 🚀 Features

- **Advanced Routing:** Built with Next.js App Router for optimized performance.
- **Dynamic Content:** Dynamic routing for individual blog posts.
- **Responsive Design:** Mobile-friendly, modern UI using CSS Modules.
- **Robust UX:** Integrated loading and error states for a seamless browsing experience.
- **Clean Architecture:** Service-oriented design for data fetching.

## 📁 Project Structure

```text
src/app/
├── layout.tsx         # Root layout
├── page.tsx           # Home page
├── posts/             # Posts module
│   ├── page.tsx       # Posts listing
│   ├── [id]/          # Dynamic post details
│   ├── new/           # Create post page
│   ├── service.ts     # API data service
│   └── loading.tsx    # Loading state
└── types/             # TypeScript definitions
```

## 🛠️ Technology Stack

- **Framework:** Next.js 13+ (App Router)
- **Language:** TypeScript
- **Styling:** CSS Modules
- **Architecture:** Server Components & Service-based data fetching

## 🚦 Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run the development server:**
   ```bash
   npm run dev
   ```

3. **View the site:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📱 Pages and Features

### Home Page (/)
- Clean, minimalist landing page design.
- Introduction to the blog platform.
- Direct navigation to blog posts.

### Posts Page (/posts)
- Organized list of all blog posts.
- Clear post titles and preview content.
- Efficient loading of post data.
- Responsive grid layout.

### Individual Post Page (/posts/[id])
- Full post content display.
- Easy navigation back to the posts list.
- Clear error states if a post is not found.
- Optimized reading experience.

## 🛣️ Routing Structure
- **App Router:** Fully utilized for modern navigation.
- **Dynamic Routes:** Handles individual posts via `[id]`.
- **Nested Layouts:** Maintains consistent UI structure.
- **Route Segments:** Specialized loading and error states for each segment.

## ⚙️ Configuration

Create a `.env.local` file in the root directory if environment variables are required.

## 📝 Notes
- Requires Node.js 14.0 or higher.
- Built with modern JavaScript/TypeScript features.
- Uses CSS Modules for scoped, clean styling.

---
*Built with ❤️ by [Heli Bhadeshiya](https://github.com/heli04)*
