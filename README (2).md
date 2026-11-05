# AI in Education and Research Symposium

The official website for **AI in Education and Research**, a one-day symposium hosted by the University of Michigan–Flint College of Innovation & Technology (CIT).

🔗 **Live site:** `https://<your-username>.github.io/<repo-name>/` *(update this once GitHub Pages is enabled)*

---

## About the Event

AI and computing are increasingly used across every field of study. They are changing how students learn, how faculty teach, and how research is conducted. This symposium brings together faculty and students from within and across disciplines, at UM-Flint and other institutions across Michigan, to discuss these changes.

| | |
|---|---|
| **Date** | To be announced (Winter 2027) |
| **Time** | 10:00 a.m. – 3:00 p.m., followed by an optional 30-minute session |
| **Location** | University of Michigan–Flint |
| **Format** | One-day, in-person symposium |
| **Expected attendance** | 150–200 participants |

### Program Highlights

- Keynote from a leading educator and expert on AI in education
- Panel on faculty–student perspectives
- Panel on university-level perspectives (centers for teaching and learning)
- Small-group discussions on shared-interest topics
- Individual faculty presentations
- Student poster session with poster awards
- Snacks and lunch provided
- Optional session on national AI resources such as NAIRR

---

## Repository Structure

```
.
├── index.html   # The entire website (HTML + CSS in one file)
└── README.md    # This file
```

The site is a single, self-contained HTML page with no build step and no dependencies. The only external resource is Google Fonts (Fraunces and Inter).

---

## Deploying with GitHub Pages

1. Push `index.html` and `README.md` to the `main` branch of this repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the **`main`** branch and the **`/ (root)`** folder, then click **Save**.
5. After a minute or two, the site will be live at `https://<your-username>.github.io/<repo-name>/`.

GitHub Pages republishes automatically every time a change is pushed to `main`.

---

## Updating the Site

All content lives in `index.html`. Common edits:

| What to change | Where to find it in `index.html` |
|---|---|
| Date, time, location | The `facts` block in the `<header class="hero">` section |
| Overview text | `<section id="about">` |
| Goals | `<section id="goals">` (one `card` per goal) |
| Program items | `<section id="program">` (one `item` per session) |
| Audience | `<section id="audience">` |
| Organizer contacts | `<section id="contact">` |
| Colors | CSS variables under `:root` at the top of the `<style>` block |

To preview changes locally, open `index.html` in any web browser.

### Planned Updates

- [ ] Confirm the event date
- [ ] Confirm the venue (room)
- [ ] Add keynote speaker and panelists
- [ ] Add a detailed agenda with session times
- [ ] Add the call for faculty presentations and student posters
- [ ] Add a registration link
- [ ] Add co-sponsor logos

---

## Organizers

- **Faculty Lead:** Murali Mani ([mmani@umich.edu](mailto:mmani@umich.edu))
- **Student Organizers:** Thi Thanh Thuy Nguyen ([ngthuy@umich.edu](mailto:ngthuy@umich.edu)) and Ameen Vathmattom Ashraf ([ameenva@umich.edu](mailto:ameenva@umich.edu))
- **CIT Administrative Support:** Laurel Ming

---

© 2026 University of Michigan–Flint, College of Innovation & Technology
