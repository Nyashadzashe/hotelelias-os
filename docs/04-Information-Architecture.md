# Hotel Elias
## Information Architecture

Version 1.0

Purpose
Define every page, feature, route and relationship within the Hotel Elias ecosystem.

## Site Hierarchy
Hotel Elias

Hotel Elias

│
├── Arrival
│
├── Home
│
├── Music
│   ├── Discography
│   ├── Albums
│   └── Singles
│
├── Videos
│   └── Music Videos
│   └── Behind The Scenes
│
├── Journal
│   ├── Hotel Logbook
│   ├── Stories
│   ├── Photography
│   └── Release Notes
│
├── Merch
│   ├── Clothing
│   ├── Accessories
│   ├── Vinyl
│   └── Checkout
│
├── Shows
│   ├── Upcoming
│   ├── Past Shows
│   └── Tickets
│
├── Gallery
│
├── About
│
├── Contact
│
└── Admin

## Public Routes
/

Home

/music

Music

/music/albums

Albums

/music/singles

Singles

/videos

Music Videos

/journal

Hotel Logbook

/journal/:slug

Journal Entry

/gallery

Gallery

/merch

Store

/shows

Shows

/about

About

/contact

Contact

## Private Routes
/admin

Dashboard

/admin/music

Manage Releases

/admin/videos

Manage Videos

/admin/posts

Manage Journal

/admin/merch

Products

/admin/shows

Shows

/admin/media

Media Library

/admin/users

Guest Accounts

/admin/settings

Website Settings

## Music Architecture
Music
↓
Discography
↓
Albums
↓
Singles

## Video Architecture
Videos
↓
Music Videos
↓
Behind The Scenes
↓
Short Films

**Each video contains:**
Thumbnail
Description
Release Date
Credits
Related Release

## Hotel Logbook
Stories
Creative Notes
Photography
Travel
Behind The Music
Announcements

Example:

Entry #021
The first demo sounded nothing like the final version...

## Merch Architecture
Merch
↓
Collections
↓
Product
↓
Checkout

Every product contains:
Story
Images
Materials
Size Guide
Shipping
Related Products

## Gallery
It exists purely for photography
Gallery
↓
Collection
↓
Photos

## Shows
Shows
↓
Upcoming
↓
Past Shows
↓
Tickets

Each event includes:
Venue
City
Country
Date
Time
Supporting Acts
Ticket Link
Gallery (after the show)

## About
Insted of a traditional biography
The Beginning
↓
The Vision
↓
The Music
↓
The Future

## Contact
Management
Bookings
Collaborations
Press
General Enquiries

## Footer
Music
Videos
Journal
Shows
Merch
Gallery
About
Contact
Instagram
Spotify
Apple Music
YouTube
TikTok

## Content Relationships
Nothing should exist in isolation

Release
↓
Music Video
↓
Journal Entry
↓
Merch Collection
↓
Live Performance

## Content Models
**Release**
Title
Type (Album / EP / Single)
Cover Artwork
Tracklist
Release Date
Platforms
Description
Producer
Songwriter
Mix & Master
Artwork Credits
Related Videos

## Video
Title
Thumbnail
Video Type
Description
Release Date
Related Release
Credits

## Journal Entry
Title
Body
Category
Images
Tags
Published Date

## Show
Venue
City
Country
Date
Time
Ticket Link
Status

## Product
Name
Description
Price
Images
Stock
Sizes
Materials
Category

## Navigation Philosophy
Music
Videos
Journal
Shows
Merch
Gallery
About

## Future Expansion
Hotel Elias
↓
Website
↓
Mobile App
↓
Fan Club
↓
Archive
↓
Podcast
↓
Studio

## Information Architecture Principles
Every page has one purpose.
Everything connects.
No dead ends.
Navigation should feel effortless.
Music always comes first.
Content should age gracefully.
Less, but better.

