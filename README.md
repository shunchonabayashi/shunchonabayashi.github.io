# Shun Chonabayashi academic homepage

Quarto source for https://shunchonabayashi.github.io.

## Edit and preview

Install Quarto 1.11.9 or newer from https://quarto.org/docs/get-started/.
Run `quarto preview` in this folder. Edit the `.qmd` files; the preview updates automatically.
Run `quarto render` to produce the complete website in `_site/`.

| File | Content |
| --- | --- |
| `index.qmd` | Homepage and highlights |
| `research.qmd` | Publications, ongoing research, and presentations |
| `cv.qmd` | CV download and its last-updated date |
| `Global_Citizenship_Lab.qmd` | Lab, teaching, mentoring, and student achievements |
| `media.qmd` | Media and public outreach |
| `Japanese.qmd` | Japanese profile |
| `hiring.qmd` | Research opportunities |
| `contact.qmd` | University contact details |
| `_quarto.yml` | Navigation, search, site metadata, and output settings |
| `styles.scss` | Visual design and responsive layout |

## Publish

The GitHub Actions workflow renders and deploys the site whenever a commit is pushed to `main`.
GitHub repository Settings → Pages must use **GitHub Actions** as the source.
The workflow can also be run manually from the Actions tab.

The publishing workflow generates `sitemap.txt` from Quarto's `sitemap.xml`, keeping both lists synchronized. The text version provides an additional sitemap submission for Google; the original XML sitemap remains available.

## Update the CV

Replace `assets/CV_Shun_Chonabayashi.pdf` with the public academic CV and update the date in `cv.qmd` to the actual CV revision date. Do not upload the private AIIB CV, which contains personal contact information.

## Maintenance

Update `date-modified` on a content page when its content changes. The CV revision date is independent of the website migration date. Retain the existing output filenames when possible so inbound links continue to work.

Content migrated from the existing university website files on November 8, 2026. The original university site was not modified. The CV is the November 8, 2026 academic version. Verify time-sensitive opportunities and forthcoming presentations when updating them.
