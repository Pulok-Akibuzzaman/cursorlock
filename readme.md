# CursorLock Neon Demo

A fun browser-based authentication experiment that combines:

- Password checking
- Remembered cursor position
- Cursor-radius verification
- Neon glassmorphism styling
- Animated scan lines
- Floating connected particles
- Mouse-reactive particle repulsion
- Animated success screen

## Live demo

After enabling GitHub Pages, your website will be available at a URL similar to:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## Running locally

Download or clone the repository, then open `index.html` in a browser.

For the most reliable local testing, run a simple web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How it works

1. Create a demo account.
2. Enter a username and password.
3. Move your mouse into the capture area.
4. Click **Capture position**.
5. Log in using the same username and password.
6. Move your mouse inside the displayed target circle.
7. Click **Check password and cursor**.
8. If both checks succeed, the animated success screen appears.

## Important security warning

This is a fun front-end demonstration only.

The account is stored in the browser's `localStorage`. Users can inspect, modify, or delete the stored data. It should not be used for real authentication, sensitive accounts, or production security.

A real authentication system would require:

- A backend server
- Secure password hashing such as Argon2 or bcrypt
- Server-side sessions
- HTTPS
- Rate limiting
- Account recovery
- Secure database storage
- Protection against replay and browser manipulation

## GitHub Pages deployment

1. Create a GitHub repository.
2. Upload `index.html` and `README.md`.
3. Open the repository's **Settings** page.
4. Select **Pages**.
5. Choose **Deploy from a branch**.
6. Select the default branch and the `/root` folder.
7. Save the settings.
8. Wait for GitHub Pages to publish the website.

## Credits

Created as a browser experiment with assistance from:

- **OpenAI ChatGPT**
- **GitHub Copilot**

The visual design, particle effects, cursor interaction, and demo logic were created for educational and entertainment purposes.