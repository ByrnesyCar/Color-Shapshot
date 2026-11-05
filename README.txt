Color Snapshot + Brevo

Upload the contents of this folder to the ROOT of your existing GitHub repository, preserving the netlify/functions folder.
Files: index.html, netlify.toml, netlify/functions/send-color-snapshot.js.
Do NOT upload your Brevo API key. It must stay in Netlify environment variables as BREVO_API_KEY with Functions scope.
Sender address in function: rebecca@bex-group.com (verified/authenticated in Brevo).
After GitHub deployment, complete a test consultation and click Email My Color Snapshot. Verify arrival in inbox and Brevo transactional logs.
IMPORTANT: The function currently accepts unauthenticated requests from the public website. Before broader public launch/licensing, add bot protection, rate limits and appropriate privacy/retention controls.
