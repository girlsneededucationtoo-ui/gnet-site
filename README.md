# GNET Initiative — Girls Need Education

A hand-coded HTML/CSS/JS website rebuilt from the original Wix layout for the **Girls Need Education (GNET) Initiative**, a nonprofit providing financial aid and advocacy for girls' education in rural Africa and the Middle East.

## Project Structure

```
gnet-site/
├── index.html          ← Homepage
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Navigation + scroll animations
├── images/             ← Add your own images here
└── pages/
    ├── blog.html
    ├── groups.html
    ├── events.html
    ├── book-online.html
    └── take-action.html
```

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Homepage with hero, mission, financial support, impact stats, marquee, ambassador form |
| `pages/blog.html` | Blog post grid |
| `pages/groups.html` | Community groups feed + sidebar |
| `pages/events.html` | Upcoming events grid |
| `pages/book-online.html` | Services booking (Partnership Session, Funding Workshop, Awareness Seminar) |
| `pages/take-action.html` | Full ambassador application form |

## Impact Stats

- **12 Countries** reached
- **45 NGO Collaborations**
- **200K Lives Affected**

## How to Run Locally

Just open `index.html` in your browser — no build tools needed!

```bash
# Optional: use a simple local server
npx serve .
# or
python -m http.server 8000
```

## How to Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload all files (drag & drop or git push)
3. Go to **Settings → Pages**
4. Set source to **main branch / root**
5. Your site will be live at `https://yourusername.github.io/repo-name`

## Adding Your Own Images

Place your images in the `/images/` folder and update the `src` attributes in the HTML files. Current placeholder images use Unsplash URLs.

## Contact

**Columbus, OH**  
collaborations@gnet-initiative.org
