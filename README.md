# Countermeasure Application — JSW Motors demo

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome or Edge, or open the folder in VS Code and use Live Server.
3. Create a request and test its workflow status.

## Publish using GitHub Pages
1. Create a GitHub repository (or open your existing one).
2. Upload `index.html` to the repository root.
3. Commit/push to `main`.
4. Open Settings → Pages.
5. Choose Deploy from a branch, select `main` and `/ (root)`, then Save.
6. Use the live URL displayed in Settings → Pages.

## Important demo limitations
- Data is stored in localStorage in the current browser only; it does not sync across laptops or users.
- This is a front-end demo and does not implement real role-based authentication, shared database, or email notifications.
- Status values follow the demo workflow: R = Open, O = In Progress/Discussion, Y = Countermeasure Finalized, B = Under Verification, G = Closed.
- For production use, connect an approved backend/database, permissions, and email service.
