<a name="readme-top"></a>

# Aora - Full-Stack AI Video Sharing Platform using Expo & React Native

![Aora - Full-Stack AI Video Sharing Platform using Expo & React Native](/.github/images/img_main.png "Aora - Full-Stack AI Video Sharing Platform using Expo & React Native")

## Getting Started

1. Make sure **Git** and **NodeJS** is installed.
2. Clone this repository to your local computer.
3. Create `.env.local` file in root folder.
4. Contents of `.env.local`:

```env
# .env.local

# appwrite project
EXPO_PUBLIC_APPWRITE_PLATFORM=com.example.aora
EXPO_PUBLIC_APPWRITE_PROJECT_ID=000000000000000000000000000

# appwrite database
EXPO_PUBLIC_APPWRITE_DATABASE_ID=000000000000000000000000000

# appwrite collection
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=000000000000000000000000000

# appwrite video
EXPO_PUBLIC_APPWRITE_VIDEO_ID=000000000000000000000000000

# appwrite storage
EXPO_PUBLIC_APPWRITE_STORAGE_ID=000000000000000000000000000
```

5. Open terminal in root directory. Run `npm install --legacy-peer-deps` or `yarn install --legacy-peer-deps`.

6. Install Expo Cli using `npm i -g expo-cli` or `yarn global add expo-cli` to initialize your app on Expo.

### 7. Set Up Appwrite

1. **Install Appwrite**:

   - If you haven't already, follow the [Appwrite installation guide](https://appwrite.io/docs/installation) to set up Appwrite on your server or use Appwrite Cloud.

2. **Create a New Project**:
   - Log in to your Appwrite console.
   - Click on the "Add Project" button.
   - Name your project (e.g., "Aora") and click "Create".

### 8. Obtain the Project ID

1. **Navigate to Your Project**:
   - Go to the project you just created.
2. **Copy the Project ID**:
   - In the project settings, you will find the "Project ID". Copy this ID.

### 9. Configure Appwrite Platform

1. **Add a New Platform**:
   - Within your project, navigate to the "Platforms" section.
   - Click on "Add Platform" and select the appropriate platform for your project (e.g., Web, iOS, Android).
   - Provide the necessary details such as domain or package name (e.g., `com.example.aora`).
   - Save the platform settings.
2. **Copy the Platform ID**:
   - After adding the platform, note the Platform ID (if provided) or use the domain/package name you added.

### 10. Set Up Appwrite Database

1. **Create a New Database**:
   - In your project dashboard, navigate to "Database".
   - Click on "Add Database", provide a name for your database, and save it.
2. **Copy the Database ID**:
   - After creating the database, copy the Database ID.

### 11. Set Up Appwrite Collection

1. **Create a New Collection**:
   - Within the Database section, click on the "Add Collection" button.
   - Provide a name for your collection and configure the necessary attributes and permissions.
   - Save the collection.
2. **Copy the Collection ID**:
   - After creating the collection, copy the Collection ID.

### 12. Obtain the Video ID

1. **Upload a Video File** (if applicable):
   - Navigate to the "Storage" section in your Appwrite console.
   - Click on "Add File" and upload your video file.
2. **Copy the Video File ID**:
   - After the upload is complete, copy the File ID of the video.

### 13. Set Up Appwrite Storage

1. **Configure Storage Bucket** (if applicable):
   - In the "Storage" section, you may need to create a new bucket or use the default bucket.
   - Ensure the bucket is configured to store your required files.
2. **Copy the Storage ID**:

   - Note the Storage Bucket ID or the specific ID used for storage configuration.

3. Now app is fully configured :+1: and you can start using this app using `expo start`.

**NOTE:** Please make sure to keep your API keys and configuration values secure and do not expose them publicly.

## Screenshots:

<p align="center">
<img src="/.github/images/img1.png" alt="Functional Sign In and Sign Up" height="700" title="Functional Sign In and Sign Up" />
<img src="/.github/images/img2.png" alt="Modern UI/UX" height="700" title="Modern UI/UX" />
</p>

<p align="center">
<img src="/.github/images/img3.png" alt="Upload AI Videos" height="700" title="Upload AI Videos" />
<img src="/.github/images/img4.png" alt="View your Profile" height="700" title="View your Profile" />
</p>

## Tech Stack

[![React JS](https://skillicons.dev/icons?i=react "React JS")](https://react.dev/ "React JS") [![JavaScript](https://skillicons.dev/icons?i=js "JavaScript")](https://developer.mozilla.org/en-US/docs/Web/JavaScript/ "JavaScript") [![CSS](https://skillicons.dev/icons?i=css "CSS")](https://developer.mozilla.org/en-US/docs/Web/CSS "CSS") [![Tailwind CSS](https://skillicons.dev/icons?i=tailwind "Tailwind CSS")](https://tailwindcss.com/ "Tailwind CSS") [![Babel](https://skillicons.dev/icons?i=babel "Babel")](https://babeljs.io/ "Babel")

