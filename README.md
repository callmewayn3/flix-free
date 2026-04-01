# FlixFree · Watch Instantly

FlixFree is a responsive, modern, and interactive web platform for streaming movies and series. It features a Netflix-style dynamic hero banner, trending sections, and playable media via a modal video player.

## Features

- **Dynamic Hero Banner:** Smooth fading hero posters showcasing trending media.
- **Trending, Movies, and Series Sections:** Horizontally scrollable sliders with movie/series cards.
- **Playable Media:** Clicking on a card opens a modal with an embedded video player.
- **Interactive Modal:** Play, pause, and close modal functionality.
- **Feedback Section:** Links to social media platforms for user feedback.
- **Responsive Design:** Works on desktop and mobile devices.
- **Free Media Labels:** Cards display a "FREE" badge.

## Technologies Used

- **HTML5 & CSS3:** Structure and styling.
- **JavaScript:** Dynamic content rendering, hero banner rotation, and modal functionality.
- **Font Awesome:** Social media icons.
- **Vimeo Embed:** Streaming video content in the modal.

## File Structure


## How It Works

1. **Hero Banner Rotation**
   - Cycles through `allHeroMedia` every 7 seconds with a smooth fade animation.
   - Clicking "Watch Now" plays the current hero media in the modal.

2. **Movie & Series Sliders**
   - Each section (`Trending`, `Movies`, `Series`) dynamically renders cards from `mediaLibrary`.
   - Clicking a card opens the embedded video in a modal.

3. **Modal Player**
   - Shows the video player (`iframe`) and media details.
   - Close the modal using the "×" button.
   - Page scroll is disabled while the modal is open.

4. **Feedback Section**
   - Links to social media platforms for feedback.

## Customization

- **Add Movies or Series**
  - Add objects to `mediaLibrary.movies` or `mediaLibrary.series`.
  - Required fields: `title`, `year`, `type`, `desc`, `embed`, `poster`.
- **Hero Banner**
  - Includes all media from trending, movies, and series arrays.
  - Change rotation interval in `setInterval(updateHeroPoster, 7000)` (milliseconds).

## Deployment Instructions

Follow these steps to deploy your website online for free:

### Option 1: GitHub Pages

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and create a new repository.
   - Name it e.g., `flixfree`.

2. **Upload Files**
   - Upload `index.html` and `README.md` (and any additional assets like images or CSS if separate).

3. **Enable GitHub Pages**
   - Go to `Settings → Pages`.
   - Under `Source`, select `main` branch and `/root`.
   - Click `Save`. GitHub Pages will provide a URL like `https://username.github.io/flixfree`.

4. **Access Your Website**
   - Open the provided URL in a browser to view your live site.

### Option 2: Netlify

1. **Sign Up / Log In**
   - Go to [Netlify](https://www.netlify.com/) and create an account.

2. **Drag & Drop Deployment**
   - In the Netlify dashboard, click `Add new site → Deploy manually`.
   - Drag the folder containing `index.html` (and assets) into the upload area.

3. **Access Your Site**
   - Netlify will provide a live URL you can share.

### Option 3: Vercel

1. **Sign Up / Log In**
   - Go to [Vercel](https://vercel.com/) and create an account.

2. **New Project**
   - Click `New Project → Import from GitHub`.
   - Connect your repository containing `index.html`.

3. **Deploy**
   - Click `Deploy`. Vercel provides a live URL for your website.

## Usage

1. Open the live website URL in any modern browser.
2. Scroll through trending, movies, or series sections.
3. Click "Watch Now" in the hero or a media card to play the video in the modal.
4. Use the feedback section to connect via social media.

## Credits

- **Font Awesome:** For icons
- **Vimeo:** Video streaming embed
- Placeholder images from [via.placeholder.com](https://via.placeholder.com/)

---

**Author:** Waynton Kibagendi  
**Email:** wayntonkibagendi@gmail.com  
**Telephone:** 0716894589
