# SocialNetDB

**SocialNetDB** is a database schema designed for a social networking platform. It efficiently manages users, posts, comments, images, links, and friendships, providing a comprehensive structure for social interactions.

## Features
- **Users**: Stores user profiles with names, passwords, descriptions, and join dates.
- **Links**: Tracks users' external links or profiles.
- **Posts**: Manages posts with timestamps and associated users.
- **Comments**: Supports nested comments linked to posts.
- **Images**: Associates images with specific posts.
- **Blurbs**: Adds descriptive text to posts.
- **Friendships**: Tracks user relationships and their start dates.

## Database Schema
The database consists of the following tables:
1. `users`
2. `links`
3. `entries`
4. `comments`
5. `images`
6. `blurbs`
7. `friends`

## Example Data
- Sample users, links, posts, and comments are pre-inserted to demonstrate functionality.

## How to Use
1. Run the provided SQL scripts to create and populate the database.
2. Query the tables to explore relationships and data interactions.

## License
This project is open-source and available for personal and educational use.
