# ShelfWise – Library Management System (HTML, CSS & JavaScript)

This is the static, browser-only edition of ShelfWise. It uses HTML, CSS, JavaScript and the browser LocalStorage. No Python, Flask, SQLite, build command or package installation is required.

## Run on your computer
1. Extract this ZIP.
2. Open the extracted `ShelfWise-GitHub-Ready` folder.
3. Double-click `index.html`. It redirects to the login page.
4. Choose **Create first Admin account** and register.

## Publish on GitHub Pages
1. Create or open a GitHub repository.
2. Extract this ZIP on your computer.
3. Upload the *contents* of the extracted folder to the repository root (not the ZIP and not the enclosing folder). `index.html` must be visible at the top level beside `login.html`, `dashboard.html`, `css/` and `js/`.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then Save.
7. Wait for GitHub Pages to publish the site and open the provided URL.

## Publish on Vercel
1. Import the GitHub repository into Vercel.
2. Choose Framework Preset **Other**.
3. Leave Build Command empty. Set Output Directory to `.` if Vercel asks.
4. Deploy.

## Included modules
- First-time Admin registration and login
- Admin-managed Librarian accounts
- Dashboard and alerts
- Books catalog and search
- Student records
- Book issue and return workflow
- Overdue fine calculation
- Reports and CSV export

## Important limitations
- User accounts, books, students and transactions are saved in the current browser's LocalStorage. Data is not shared between different devices or browsers. Clearing browser site data can erase it.
- The login is a client-side demonstration, not server-enforced security. A visitor with technical access to the browser can inspect or change local data. Do not use real confidential student information or important passwords.
- For real multi-user access, centralized records and strong authentication, a server-side backend and database are required.
- Keep using the same published site origin to retain its LocalStorage data.
