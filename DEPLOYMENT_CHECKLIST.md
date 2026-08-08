# Deployment Checklist

Use this checklist before making the repository public or redeploying the demo.

## Required

- [ ] Confirm `.env` is not committed.
- [ ] Confirm no API keys, tokens, database URLs, passwords, resumes, or personal documents are committed.
- [ ] Confirm `node_modules`, `.venv`, `venv`, `__pycache__`, `.cache`, and runtime vector-store folders are not committed.
- [ ] Run a local syntax check: `python -m compileall .`
- [ ] Install dependencies in a clean virtual environment.
- [ ] Start the app locally and test the main demo flow.
- [ ] Verify the README describes the current project accurately.
- [ ] Verify public links use the correct GitHub, LinkedIn, Hugging Face, and portfolio profiles.

## Hugging Face Spaces

- [ ] Confirm the README front matter matches the app framework.
- [ ] Confirm `app_file` points to the correct file.
- [ ] Confirm `requirements.txt` is present at the repository root.
- [ ] Add real secrets through Hugging Face Space settings only.
- [ ] After deployment, manually open the Space and test upload/query flows.

## Recommended portfolio assets

- [ ] Add one clean screenshot of the app home screen.
- [ ] Add one screenshot of a successful result.
- [ ] Add a short GIF or walkthrough if available.
