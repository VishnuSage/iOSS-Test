# Project Structure

- frontend/ : Vite + React + Redux Toolkit + Material UI (Netlify ready)
- backend/  : Django + Django REST Framework + PostgreSQL (Render ready)


## Deployment

### Frontend (Netlify)
1. Push your code to GitHub.
2. Connect your repo to Netlify and select the `frontend` folder as the root.
3. Set build command: `npm run build`
4. Set publish directory: `dist`
5. Optionally, set up environment variables if needed.

### Backend (Render)
1. Add your repo to Render and select the `backend` folder as the root.
2. Set the build and start commands:
	- Build: `pip install -r requirements.txt`
	- Start: `gunicorn core.wsgi`
3. Set environment variables for your database (see Render docs).
4. Add a PostgreSQL database via Render dashboard and update `settings.py` accordingly.

## Next Steps
- Implement your features as per the assessment question
- Update README with any additional setup or instructions
