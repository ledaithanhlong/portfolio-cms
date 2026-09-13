# Portfolio CMS

A personal portfolio website with a custom admin CMS for managing portfolio content.

The project separates the public portfolio experience from content management, allowing profile information, skills, projects, and certificates to be updated without editing the public page directly.

## Live Portfolio

https://ledaithanhlong.vercel.app/

## Features

- Responsive personal portfolio
- Project showcase with live demo and source code
- Skills organized by proficiency level
- Certificate showcase
- Custom admin CMS
- Supabase database integration
- Supabase Authentication
- Supabase Storage
- Row Level Security (RLS)
- Contact form

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Supabase
- Vercel
- Web3Forms

## How It Works

The public portfolio loads content from Supabase, while the admin CMS provides an authenticated interface for managing that content.

```text
Public Portfolio
      │
      │ Read
      ▼
   Supabase
      ▲
      │ Auth + CRUD
      │
   Admin CMS
