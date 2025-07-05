# How to Deploy Your App to Firebase

You're so close to getting your app live! Follow these steps to get your permanent URL.

### Step 1: Set Your Firebase Project ID

1.  Open the file named `.firebaserc` in your project.
2.  Replace the text `<YOUR_FIREBASE_PROJECT_ID>` with your actual Firebase Project ID.
    *   You can find your Project ID on the [Firebase Console](https://console.firebase.google.com/). It's often next to the gear icon at the top of the page.
3.  Save the `.firebaserc` file.

### Step 2: Open Your Terminal

Open a command-line terminal on your computer (or use the one in Firebase Studio).

### Step 3: Go to Your Project Folder

The error `Not in a Firebase app directory` means you are in the wrong folder. You need to navigate into your project's main folder before deploying.

If your project is in a folder named `verdant-vision-app`, you would run this command:
```bash
cd verdant-vision-app
```
*(Replace `verdant-vision-app` with the actual name of your project folder).*

### Step 4: Deploy!

Now that you are in the correct folder, run the following commands one by one:

1.  Log in to Firebase (if you haven't already):
    ```bash
    firebase login
    ```
2.  Deploy your app:
    ```bash
    firebase deploy
    ```

After the `deploy` command finishes, it will show you your new permanent URL. It will look something like `https://your-project-id.web.app`.

You can now use this permanent URL with PWA Builder or Bubblewrap!