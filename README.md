# Flutter Navigation App

This Flutter application demonstrates screen navigation using the `Navigator` and includes a bottom navigation bar for easy access to different sections of the app.

## Code Overview

### `lib/main.dart`

This file contains the main structure of the app, including the main `MyApp` widget, the different screen widgets (`HomeScreen`, `SearchScreen`, `AddScreen`, `ReelsScreen`, `AccountScreen`), and a custom widget (`CustomWidget`). Below is an overview of each:

#### `MyApp`

- The main entry point for the app.
- Configures the `MaterialApp` and sets the `HomeScreen` as the initial screen.

#### `HomeScreen`

- The default landing screen with a basic layout, including a Flutter logo, app name, and buttons to navigate to other screens.

#### `SearchScreen`

- A screen with an app bar titled 'Search Content,' featuring a search input field and a button to trigger a search operation.

#### `AddScreen`

- A placeholder screen with an app bar titled 'Add Content.'

#### `ReelsScreen`

- A screen with an app bar titled 'Watch Content,' demonstrating a more complex layout with a grid of colored containers.

#### `AccountScreen`

- A screen with an app bar titled 'Account Content,' displaying a user's profile picture, name, and additional information.

#### `CustomWidget`

- A reusable custom widget with a blue background, used for demonstration purposes.

## Getting Started

### Prerequisites

Make sure you have Flutter installed on your machine. If not, you can follow the installation instructions [here](https://flutter.dev/docs/get-started/install).

### Clone the Repository

```bash
git clone https://github.com/your-username/HW3.git
