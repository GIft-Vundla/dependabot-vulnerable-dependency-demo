# Dependabot Demo Resource

This folder is for Q5 of the assignment. It contains an intentionally vulnerable `package.json` and `package-lock.json` so GitHub's dependency graph and Dependabot can raise alerts in a public demo repository.

Use it only in a throwaway educational repository. Do not run, deploy, or reuse these dependencies in a real application.

Suggested workflow:

1. Create a new public GitHub repository.
2. Upload or push the contents of this folder, including `.github/dependabot.yml`.
3. In GitHub, enable Dependency graph, Dependabot alerts, and Dependabot security updates if they are not already enabled.
4. Wait for GitHub to analyze the manifest and raise dependency alerts.
5. Capture screenshots of the alerts and Dependabot remediation suggestions for the assignment.
