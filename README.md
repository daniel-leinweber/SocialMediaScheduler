# Social Media Scheduler (.NET MAUI)

This Android-only .NET MAUI mobile app allows you to compose, schedule, and publish social media content across Facebook Pages, Instagram Feeds (as Reels), and YouTube channels. It supports text, images, and video posts. All posts are stored locally using SQLite. Background scheduling is handled natively on the device—there is no need for a backend server or internet connection at the time of creation.

## Key Features

- 📅 Schedule posts for future publication
- 📱 Create content on your smartphone with direct media uploads
- 📂 Local post storage using SQLite
- 🔐 Securely store and use access tokens
- 🚀 Background task engine to auto-publish when due
- 📋 Bottom tab navigation: New Post | Scheduled Posts | Settings

## 🔒 Local-Only by Design

- No backend or cloud sync is required
- All tokens, media and post jobs are stored **securely** on-device

## 🚀 Roadmap

- [x] Android Support
- [ ] Facebook / Instagram / YouTube API Integration
- [ ] Background Task Scheduler
- [ ] UI/UX Polish and Error Handling
- [ ] CI Build Script for Direct Deployment

## 🧰 Tech Stack

- .NET 8 + .NET MAUI
- SQLite via `sqlite-net`
- Android-only (manual deployment)
