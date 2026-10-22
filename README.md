# Sports Life

A Flask website that promotes an active lifestyle through sports, yoga and workouts.

## Pages

- **Home:** introduction
- **Physical Activity:** sections on Sports, Yoga and Workout
- **People / Works:** activity pages for Football, Table Tennis, Dance and Carrom
- **About**
- **Contact:** a contact form. Submissions are saved to `db.csv`, and the user sees a thank-you page.

## Project structure

| Path | Purpose |
|------|---------|
| `server.py` | Flask app: page routing and contact-form handling |
| `templates/` | HTML pages |
| `static/` | CSS (`design.css`) and JavaScript (`main.js`) |

## Getting started

```bash
pip install flask
python server.py
```

Then open http://127.0.0.1:5000.
