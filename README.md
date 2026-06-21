# Quirky Fortune — Daily Fortune

A calm, beautifully designed fortune experience that creates space for reflection and mindful moments throughout the day.

Fortu delivers a daily reading, personalized insights, and a simple, distraction-free environment for self-reflection.

Built as a Progressive Web App (PWA), Fortu works seamlessly across iPhone, Android, tablets, and desktop browsers.

## Features

* Daily fortune readings
* Reflection prompts and deeper insights
* Customizable profile with editable name and profile picture
* Local storage support to save preferences directly on the device
* Installable PWA experience for iOS, Android, and desktop
* Offline support through service workers
* Responsive, mobile-first design

## Live Demo

Replace the URL below with your deployed application:

```text
https://gefenrose.github.io/quirky-fortune/
```

## Installation

### iPhone and iPad

1. Open Fortu in Safari.
2. Tap the **Share** button.
3. Select **Add to Home Screen**.
4. Tap **Add**.

### Android

1. Open Fortu in Chrome.
2. Tap the **Install App** prompt or open the browser menu.
3. Select **Install**.

## Technology Stack

* HTML5
* CSS3
* JavaScript
* Web App Manifest
* Service Workers
* Local Storage API

## Project Structure

```text
/
├── index.html
├── manifest.webmanifest
├── sw.js
├── apple-touch-icon.png
├── icon-192x192.png
├── icon-512x512.png
├── maskable-icon-512x512.png
└── assets/
```

## Deployment

To deploy Fortu using GitHub Pages:

1. Upload the project files to the root of your repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select:

   * **Source:** Deploy from a branch
   * **Branch:** `main`
   * **Folder:** `/ (root)`
4. Save your changes.

Your application will be available at:

```text
https://gefenrose.github.io/quirky-fortune/
```

## Privacy

Fortu stores profile information and preferences locally on the user's device using Local Storage.

No accounts are required, and no personal data is transmitted or collected.

## Roadmap

* Additional fortune categories
* Saved readings and history
* Theme customization
* Notifications and reminders
* Optional cloud synchronization

## Contributing

Contributions, feature requests, and suggestions are welcome.

Please open an issue or submit a pull request to help improve the project.

## License

This project is released under the MIT License.
