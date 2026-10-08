# Khushi Pudasaini — Cybersecurity Portfolio v2

Blue/purple themed responsive cybersecurity portfolio built as a static website and served through Nginx with Docker Compose.

## Included

- Modern blue + purple cybersecurity theme
- Animated SVG network/security graphic
- Responsive mobile navigation
- Scroll reveal animations
- About / career focus
- Detailed cybersecurity skills
- Six portfolio projects
- CTF / TryHackMe section
- Tools ticker
- Education / current learning / technical environment
- Certification section
- Other skills
- Contact section
- Nginx security headers

## Run locally

Requirements:

- Docker Desktop, or Docker Engine + Docker Compose

From the project directory:

```bash
docker compose up -d
```

Then open:

```text
http://localhost:8080
```

Stop it with:

```bash
docker compose down
```

## Project structure

```text
khushi-portfolio-v2/
├── docker-compose.yml
└── site/
    ├── index.html
    ├── styles.css
    ├── script.js
    └── nginx.conf
```

## Things to replace later

Search `site/index.html` for these placeholder contact items:

- GitHub
- TryHackMe
- Hack The Box
- Email

The LinkedIn profile is already included:

`https://linkedin.com/in/khushi-pudasaini-4a3a46352`

## Live editing

The site directory is mounted directly into Nginx. Edit files under `site/` and refresh your browser.
