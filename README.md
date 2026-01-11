# 🎂 Happy Birthday Proposal Page

A beautiful, interactive, and mobile-responsive birthday wish page that culminates in a romantic marriage proposal.

## ✨ Features

- **Hero Section**: Full-screen landing with floating animations (balloons, hearts), glassmorphism effect, and vibrant gradient typography.
- **Gallery**: "Our Moments" section to showcase your favorite memories.
- **Heartfelt Message**: A special message section (currently in Gujarati) with a parallax background.
- **Proposal**: A dramatic "Will You Marry Me?" reveal.
- **Interactive "YES!" Button**: Triggers a celebration video overlay and confetti explosion.
- **Background Music/Video**: Integrated video playback for the special moment.

## 🚀 How to Use

1.  **Clone or Download**: Get this code onto your computer.
2.  **Customize Images**:
    -   Replace images in the `assets/` folder:
        -   `hero_bg.png`: Hero section background.
        -   `proposal_bg.png`: Proposal section background.
        -   `Image1.jpeg`, `image2.jpeg`, etc.: Gallery images.
    -   Ensure filenames match or update `index.html` to match your new filenames.
3.  **Customize Video**:
    -   Replace `assets/video.mp4` with your own proposal/birthday video.
4.  **Customize Text**:
    -   Open `index.html` and edit the text in the `hero-content`, `message`, and `proposal` sections.

## 🌐 Deployment (GitHub Pages)

To host this page for free on GitHub Pages:

1.  **Initialize Git**:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```

2.  **Create a Repository on GitHub**:
    -   Go to GitHub and create a new repository (e.g., `my-birthday-wish`).
    -   Do not initialize with README/gitignore (since you have them locally).

3.  **Push to GitHub**:
    ```bash
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
    git push -u origin main
    ```

4.  **Enable GitHub Pages**:
    -   Go to your repository **Settings** > **Pages**.
    -   Under **Source**, select `main` branch and `/ (root)` folder.
    -   Click **Save**.
    -   Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

## 🛠️ Technologies Used

-   HTML5
-   CSS3 (Flexbox, Animations, Glassmorphism)
-   JavaScript (Intersection Observer, DOM Manipulation)
