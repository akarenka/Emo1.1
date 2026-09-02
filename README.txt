EmoStream Sharing v5

New sharing features
- Share button on every video/audio card.
- Share button in Favorites.
- Share Playlist button on every playlist.
- Uses the native share sheet on supported phones and browsers.
- Copies the website URL and share text on desktop browsers without Web Share support.
- Does not include the Cloudflare R2 or Firebase Storage source media URL.

All existing functions are retained, including Firebase ad sync, playlists,
auto-loop, manager authentication, uploads, delete/remove controls, avatar,
R2 Worker support, and no-right-click media protection.

Deployment
1. Replace the current website index.html with the index.html in this package.
2. Keep the currently published combined Firestore rules. The package also
   contains the combined rules as firestore.rules for backup.
3. Redeploy the website and refresh with Ctrl+F5.
