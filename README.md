# Ultimate Gaming Community Management System (UGCMS)

## Overview

The Ultimate Gaming Community Management System (UGCMS) is an all-in-one platform designed for community owners to manage and enhance their gaming communities. From managing user roles to handling donations, bans, and in-game statistics, UGCMS offers a comprehensive set of tools.


## Why?

Well, I was honestly tired of having multiple ban systems and donation systems across different types of games. Garry's Mod, (Team Fortress 2 and other Source Games use SourceMod), GoldSrc, and Sven Co-Op even have different systems. I just wanted one system to cover as many games as I can, and to be able to integrate any game it can't be used for easily using an API. Below is a breakdown of the platform’s robust features.

## Features

### Seamless Social Integration

- Sync Profiles with Steam & Discord: Users and staff can easily log in and link their profiles using Steam and/or Discord. You have full control over which linked social profiles appear on your page.
- API Integration: Display relevant social data via API calls to Steam and Discord.

### Effortless Ban Management Across Platforms

- Multi-Game Ban Support: Easily manage bans and unbans across a variety of popular gaming platforms, including:
  - Source Engine Games/Mods (e.g., Counter-Strike, TF2)
  - GoldSrc Engine Games/Mods (e.g., Half-Life, Day of Defeat)
  - Minecraft server integration for various platforms (Spigot, CraftBukkit, Forge)
  - Make your own support! Your game isn't supported? Use the API to code your own plugin to interface with the website
  - Advanced Ban Features: Import SourceBans, AMXBansX, and more!

### Comprehensive Analytics & Audit Logs

- Track User Engagement: Staff can access detailed analytics about user activities on the site, such as:
  - Visitor statistics
  - Ban and donation data
  - Audit logs for transparency
  - And more…

### Streamlined Donation Management

- Support for Donations: Easily manage donation packages and payment processing.
  - Stripe: Process payments with debit/credit cards via Stripe (Card Brands Supported)
  - PayPal: Users can donate through PayPal with a quick login process.
  - Subscription or One-Time Payments: Offer recurring packages with clear labeling for both subscriptions and one-time payments.

### Engage with Gamification

- Reward User Activity: Enable a toggleable gamification system to incentivize user participation.
- Level Up: Sync users’ level progression with Discord and/or game servers.
- Custom Rewards: Create personalized rewards for active users, such as badges, experience bonuses, and stickers.

### Permission System
- Set up expansive "groups" with permissions to access.
- Choose a default group that all users receive when they create an account.
- Web permission groups can be set seperately per section of the website (donation system, ban system, ad stats, profile management, gamification, site settings, static page generation, and audit logs)
- Gameserver permission groups can be set seperately per server, per game mod/engine (Source, GoldSrc, etc.), or globally.
- Superadmin group can be given to enable all permissions.
- Override permissions per-user to allow for even more customization of access.

### Ad Management
- Eaily integrate banner ads, popup ads, popunder ads, and interstitial ads into the site.
- View and manage statistics on ad performance.
- Ads can be toggled to be hidden with permissions.
- Export stats to CSV (Comma-separated values), Excel, PDF, or all three!

### Customizable Webpages

- Easy-to-Use WYSIWYG Editor: Create and edit both static and dynamic web pages to suit your community's needs.
  - Static Pages: Ideal for MOTD (Message of the Day), announcements, or other non-changing content.
  - Dynamic Pages: Perfect for creating custom loading screens (e.g., for Garry’s Mod servers).

### Developer-Friendly Features

- Built with Laravel: The platform is built using the powerful Laravel PHP framework, ensuring modularity and scalability.
- Tailwind CSS: Enjoy a clean, custom design with Tailwind CSS.
- Secure Client-Side Code: Client-side code is obfuscated for added security when using npm run buildcss.
- Multiple Database Support:
  - Default: MySQL
  - Alternatives: PostgreSQL, Redis, MariaDB, SQLite, SQL Server 2017+, MongoDB
  - RESTful API: Easily integrate UGCMS with other applications using our secure API.

## Installation

- Coming Soon: A detailed installation guide will be available in INSTALL.md.

## Pricing

### No Obligation, Cancel Any Time
- $30 USD per month basic plan
  - Monthly bills
- Lifetime updates
- Digital rights management (DRM) Enabled
### Minimum Commitment
- $29 USD per month with 3 month contract
  - Bills for $87/quarter
- Lifetime updates
- Digital rights management (DRM) Enabled
### Startup Community
- $28 USD per month with 6 month contract
  - Bills for $174/semi-annually (every 6 months)
- Lifetime updates
- Digital rights management (DRM) Enabled
### Established Community
- $27 USD per month with 12 month contract
  - Bills for $336/yearly
- Lifetime updates
- Digital rights management (DRM) Enabled
### Enterprise Edition
- Bills for $624
  - One-Time for a Lifetime License
- No Anti-Piracy Features
- Most overall savings
- Lifetime updates
- Comes with source code

## Bug Reports

- See ``SECURITY.md`` for vulnerability reporting. All other reports of minor bugs can be reported normally.
