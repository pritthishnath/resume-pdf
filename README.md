## PDF Resume

The résumé served at [resume.pritthishnath.com](https://resume.pritthishnath.com).

It is written in LaTeX (a single-column `article` layout set in Latin Modern) and kept ATS-friendly: real text, standard section headings, full URLs and plain separators. `index.pdf` is the compiled output; the LaTeX source lives in a separate repository.

### Publishing

A push to `main` runs the CD workflow, which copies `index.pdf` to the web server over SSH. Caddy serves it at the address above.
