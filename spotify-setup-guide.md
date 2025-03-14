# Setting Up Spotify Integration for GitHub Profile

This guide will help you set up the Spotify "Now Playing" widget for your GitHub profile README.

## Method 1: Using spotify-github-profile (Recommended)

This method is the simplest and requires no maintenance:

1. **Visit the Setup Page**:
   - Go to: https://spotify-github-profile.vercel.app/api/login
   - Click on "login" with your Spotify account

2. **Authorize the Application**:
   - Log in with your Spotify credentials
   - Authorize the app to access your Spotify data

3. **Choose Your Theme**:
   - After authorization, you'll be presented with different theme options
   - Select the theme you prefer (I recommend "natemoo-re" for a sleek dark theme)
   - Customize colors if desired

4. **Copy the Generated Markdown**:
   - The site will generate markdown code for your README
   - Copy this code (it includes your Spotify user ID)

5. **Update Your README**:
   - Replace the placeholder in your README with the code you copied
   - Replace both instances of `YOUR_SPOTIFY_USER_ID` with your actual Spotify user ID

## Finding Your Spotify User ID

If you need to find your Spotify User ID manually:

1. Open Spotify
2. Click on your profile in the top-right corner
3. Select "Profile" from the dropdown
4. In the URL, look for the string after "user/" - that's your user ID
   Example: https://open.spotify.com/user/12345678 (12345678 is your user ID)

## Alternative Themes

The spotify-github-profile offers several themes:
- natemoo-re (shows album art with a progress bar)
- karaoke (lyrics if available)
- novatorem (minimalist design)

To change themes, update the `theme=` parameter in the URL.

## Troubleshooting

If your widget isn't showing your current song:

- Make sure you've played something recently on Spotify
- Check that your account is connected correctly
- Ensure you're using the correct Spotify user ID

Note: The widget shows "Offline" when you're not currently playing music, which is normal behavior.

## Other Options

If you prefer a different approach, you can also try:
- [novatorem/novatorem](https://github.com/novatorem/novatorem) (requires Vercel deployment)
- [kittinan/spotify-github-profile](https://github.com/kittinan/spotify-github-profile) (the one we're using above)
- [tthn0/Spotify-Stats](https://github.com/tthn0/Spotify-Stats) (shows more detailed stats) 