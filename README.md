# Zocial Platform

**Zocial** is a full-stack, role-based social media platform that blends the best features of Facebook, Instagram, and Twitter (X). It enables users to share updates, connect through stories and groups, engage in real-time messaging, and explore trending content in a modern, AI-enhanced ecosystem.

---

## 📌 Table of Contents

- [Overview](#1-overview)
- [User Roles & Permissions](#2-user-roles--permissions)
- [Features & System Flow](#3-features--system-flow)
- [Navigation Structure](#4-navigation-structure)
- [UI Components](#5-ui-components)
- [Tech Stack](#6-tech-stack)

---

## 1. Overview

Zocial offers a dynamic social platform where users can post text, media, and stories; interact with each other through comments, messages, and groups; and stay updated with trends. Admins and moderators manage content and users to maintain community health, while AI features enhance user experience.

---

## 2. User Roles & Permissions

### 👤 User

- Create posts (text, image, video)
- Follow/unfollow users
- Like, comment, and share posts
- Send/receive private messages
- Join and interact in groups
- Create and view stories
- Explore trending content

### 🛡️ Moderator

- Moderate user content and reports
- Mute or suspend users
- Remove inappropriate posts/stories/comments
- Manage groups and communities

### 🧑‍💼 Admin

- Full control over platform structure
- Manage all users, roles, and permissions
- Configure navigation and trending algorithm
- View analytics dashboard (users, engagement, content trends)
- Broadcast platform-wide announcements

---

## 3. Features & System Flow

### ✅ Core Features

- Real-time posting and interactions
- Story and media sharing
- AI-powered content moderation and captioning
- Group creation and community participation
- Event creation and RSVPs
- Direct messaging with read receipts
- Follow system and personalized feeds

### 🔄 System Flow

1. User registers or logs in
2. Navigation and content load based on role
3. Users create content and interact with others
4. Moderators monitor and review flagged content
5. Admins analyze usage and maintain system configuration

---

## 4. Navigation Structure

### 🌐 Public Navigation (Unauthenticated)

- Home (`/`)
- Explore (`/explore`)
- Login (`/login`)
- Register (`/register`)

### 👤 User Navigation

- Feed (`/feed`)
- Profile (`/profile/:username`)
- Messages (`/messages`)
- Notifications (`/notifications`)
- Groups (`/groups`)
- Create Post (`/create`)
- Stories (`/stories`)
- Settings (`/settings`)

### 🛡️ Moderator Navigation

- Dashboard (`/moderator/dashboard`)
- Flagged Posts (`/moderator/posts`)
- User Reports (`/moderator/reports`)
- Manage Groups (`/moderator/groups`)

### 🧑‍💼 Admin Navigation

- Admin Dashboard (`/admin/dashboard`)
- User Management (`/admin/users`)
- Role Manager (`/admin/roles`)
- Analytics (`/admin/analytics`)
- Navigation Editor (`/admin/navigation`)
- Announcement Center (`/admin/announcements`)

---

## 5. UI Components

### 🌍 Global

- Dynamic Navbar
- Role-based Sidebar
- Notifications dropdown
- Toast alerts
- Modal dialogs
- File upload components
- Rich text/media editor

### 👤 User Components

- Post card and detail view
- Story carousel and viewer
- Follow/Unfollow button
- Group list and join view
- Chat UI (DMs)
- Profile editor and avatar upload
- Trending tags and recommendations

### 🛡️ Moderator Components

- Reported content table
- User moderation panel
- Group moderation tools
- Suspicious activity logs

### 🧑‍💼 Admin Components

- Analytics charts and KPIs
- Role and permission table
- Navigation editor (drag-and-drop with role visibility)
- Broadcast announcement form
- User ban and audit tools

---

## 6. Tech Stack

### 🖥️ Frontend

- Next.js
- TailwindCSS + shadcn/ui
- TanStack Query
- Role-based routing and layouts

### ⚙️ Backend

- Supabase (PostgreSQL + Auth + Realtime)
- Node.js

### 📦 Tools & Integrations

- Cloudinary or Supabase Storage (media uploads)
- OpenAI API (AI captions, moderation, recommendations)
- Socket.IO or Supabase Realtime (chat & live updates)
- EmailJS / Resend (notifications)
- Redis (session cache, rate limiting)

---

> This README serves as a blueprint for building **Zocial** – a feature-rich, scalable, and modular social media platform. Contributions, forks, and discussions are welcome to expand and improve the ecosystem.
