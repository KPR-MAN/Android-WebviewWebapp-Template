# Android WebView/WebApp Template

A reusable template for creating Android apps with WebView that load local HTML/CSS/JS assets.

## 🚀 Quick Start

1. **Clone this template**
   ```bash
   git clone https://github.com/YourUsername/android-webview-template.git my-app
   cd my-app
   ```bash
   git clone https://github.com/YourUsername/android-webview-template.git my-app
   cd my-app
```

1. Customize for your app
   · Update app/build.gradle - change applicationId and namespace
   · Update app/src/main/res/values/strings.xml - change app name
   · Update package structure in app/src/main/java/
   · Add your HTML/CSS/JS files to app/src/main/assets/
2. Push to GitHub
   · Create a new repository on GitHub
   · Push your code - APK builds automatically via GitHub Actions

📁 Project Structure

```
app/src/main/
├── assets/           # Web content
│   ├── html/        # HTML files (*.html)
│   ├── css/         # Stylesheets (*.css)  
│   ├── js/          # JavaScript (*.js)
│   └── images/      # Images (*.png, *.jpg)
├── java/            # Android Java code
└── res/             # Android resources
```

⚙️ Features

· ✅ WebView with modern settings - JavaScript, DOM storage, zoom controls
· ✅ Mobile-optimized - Responsive design, touch-friendly
· ✅ Automatic APK builds - GitHub Actions workflow included
· ✅ Modern Android - Latest Gradle, SDK 34, Material Design
· ✅ No deprecated APIs - Clean, working code

🔧 Customization

Change App Name

Edit app/src/main/res/values/strings.xml:

```xml
<string name="app_name">Your App Name</string>
```

Change Package Name

1. Update app/build.gradle:
   ```gradle
   namespace 'com.youraccount.yourapp'
   applicationId "com.youraccount.yourapp"
   ```
2. Update Java package directory structure

Add Your Web Content

· HTML: Add to app/src/main/assets/html/
· CSS: Add to app/src/main/assets/css/
· JS: Add to app/src/main/assets/js/
· Images: Add to app/src/main/assets/images/

📦 Building

The APK builds automatically on every push to the main branch via GitHub Actions.

Download APK: Go to your GitHub repo → Actions → Latest workflow run → Artifacts

🛠️ Local Development

```bash
# Build locally (requires Android SDK)
./gradlew assembleDebug

# Output: app/build/outputs/apk/debug/app-debug.apk
```

📄 License

[Add your license here]
