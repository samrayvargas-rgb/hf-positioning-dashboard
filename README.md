# HF Positioning vs Economic De-leveraging Dashboard

## Deploy to Netlify
1. Push this folder to a GitHub repo.
2. In Netlify: New site from Git → select the repo.
3. Build command: leave blank
4. Publish directory: `.` (or leave default)

The economic indicators attempt to pull from FRED on page load.  
For reliable live data, replace `DEMO_KEY` in index.html with a free FRED API key from https://fred.stlouisfed.org/docs/api/api_key.html

HF Positioning Heat is still manual (edit the `hfScore` variable).
