# SkillBridge — Skill Gap Analyser

## Deploy to Vercel

1. Push this repository to GitHub.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Keep the project root set to the repository root. The included `vercel.json` serves the `frontend` directory and deploys the API functions in `api`.
4. Choose **Other** if Vercel asks for a framework preset, then deploy.

The deployed site includes `/api/jobs` and `/api/analyze`; it does not need the local Java server. The API role catalog in `api/roles.json` is generated from the Java analyzer's job-role definitions.

For local development, continue using `run.bat` to build and start the Java server, then open `http://localhost:8080`.
