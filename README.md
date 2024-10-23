# News App

A simple **News App** built with **Kotlin** for Android. This app fetches news articles from a web API and allows users to save their favorite articles using a **bookmark** feature.

## Features

- **Home Screen**: Displays the latest news articles fetched from a web API.
- **Bookmark Feature**: Save articles for future reference.
- **API Integration**: Fetches news articles from a publicly available API.
- **Offline Access**: Access saved (bookmarked) articles even when offline.
- **Modern UI**: User-friendly design with intuitive navigation.

## Technologies Used

- **Kotlin**: Main language for Android development.
- **Retrofit**: For making HTTP requests to fetch data from the API.
- **Room**: For local database storage and managing bookmarks.
- **RecyclerView**: To display the list of articles efficiently.
- **ViewModel & LiveData**: To handle data and UI interactions.
- **Coroutines**: For handling asynchronous operations like network calls.

## Usage

- **Home Tab**: Displays a list of the latest news articles.
  - Tap an article to view its details.
  
- **Bookmark Articles**: 
  - Save any article by tapping the bookmark icon.
  - Bookmarked articles are stored locally.

- **Bookmark Tab**: 
  - View all saved articles from the bookmark tab.
  - Bookmarked articles are available even when offline.
