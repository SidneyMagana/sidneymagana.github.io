# Professional experience logo uploads

Upload approved organization logos to this folder using GitHub → Add file → Upload files. Prefer SVG when obtained from an official brand source, otherwise transparent PNG/WebP. Avoid screenshots containing unrelated UI.

Suggested filenames:
- google.svg
- amazon.svg
- equinox.svg
- volunteers-of-america.svg
- alameda-county-housing-authority.svg
- contra-costa-county-housing-authority.svg
- community-housing-development-corporation.svg
- sf-rents.svg
- san-leandro-police-department.svg
- the-sun-gallery.svg
- amigos-de-las-americas.svg

Use the actual supplied file extension in HTML; don't rename PNG bytes to SVG. If a logo is unavailable, keep the organization's name as text. Don't imply endorsement or partnership beyond paid work.

The experience section is in the repository root index.html, inside <section id="experience">. After uploading each logo, replace the matching text-only <li class="experience-item"> with an <li> containing an <img src="/assets/experience/FILE" alt="Organization name logo" loading="lazy"> and accessible organization name. Keep every logo contained rather than cropped.

Keep brand logos separate from employer logos. Brand manuals:
- /brand-identity/
- /sidsgermination/brand-identity/
- /pocodepaz/brand-identity/
- /backtoelsalvador/brand-identity/
