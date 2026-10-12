# HeartBeat — Real-Time Web Application

## Project Overview

**HeartBeat** is a personal web application I developed to enable real-time communication between two geographically separated users.

The application uses a two-node architecture (New York and Oslo), allowing users to exchange heartbeats, send messages, share availability statuses, and receive visual feedback through a custom interface.

Built using HTML, CSS, JavaScript, and Supabase, HeartBeat explores real-time database communication, frontend development, and cloud-based application architecture.

The project combines practical web development with a personal use case, focusing on simplicity, responsiveness, and reliable communication.

**This repository documents the project's design, architecture, functionality, and development process. The application source code is maintained in a separate private repository.**


## Technologies

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Database | Supabase PostgreSQL |
| Real-time communication | Supabase Realtime |
| Version control | Git and GitHub |
| Architecture | Two-node web application |

## Implemented Features

### Real-Time Communication
- Send and receive heartbeats between New York and Oslo nodes
- Exchange direct messages between users
- Share and update individual availability statuses
- Synchronize information between connected browser sessions

### User Interface
- Custom-designed interface with a cybersecurity-inspired theme
- Animated heartbeat transmission and reception
- Visual indicators for user and node statuses
- Dedicated status controls for Lilo
- Recent heartbeat history

### Backend and Data
- PostgreSQL database hosted on Supabase
- Real-time subscriptions for cross-node updates
- Persistent heartbeat and status information
- Browser-based node identification

## Project Architecture

HeartBeat uses a two-node design, with both browser clients communicating through Supabase.

The database stores application information, while Supabase Realtime distributes updates between connected clients.

This enables communication without requiring users to refresh the page manually.
