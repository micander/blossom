# blossom
Cross-platform web service and library for multiplayer features in PC music games, written in Rust.

The project consists of two parts:
1. A web service that stores user profiles and high scores, and enables multiplayer and text chat features
2. A shared library linked with the game acting as a middleware, passing data to and from the game in a simple, standardized, and versioned API and interacting with the web service
