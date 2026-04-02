Boteti West Football Tournament - Render Deployment

Files:
- index.html
- render.yaml

Deploy steps:
1. Create a new GitHub repository.
2. Upload index.html and render.yaml to the repository root.
3. Go to Render dashboard.
4. Click New > Static Site.
5. Connect your GitHub repository.
6. Render should detect the blueprint automatically, or create the service with:
   - Build Command: leave blank
   - Publish Directory: .
7. Deploy.

Important:
This is a static site. The hidden admin passwords are stored in frontend code and are not secure against inspection.
