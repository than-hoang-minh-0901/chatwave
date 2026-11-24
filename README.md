# ChatWave

A responsive, static chat UI demo.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository named `chatwave`.
2. Choose **Public** (or Private if your plan supports Pages for private repositories).
3. Upload `index.html` to the repository root and commit the file.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. Wait for the Pages URL to appear on the Pages settings screen.

## Important

This is a frontend demo. It stores demo messages in the visitor's own browser using local storage. It does not yet provide shared accounts or messages between different people. For real multi-user chat, connect a backend such as Supabase and configure authentication, database security policies, and realtime subscriptions. Never put a secret service-role key in browser code.
