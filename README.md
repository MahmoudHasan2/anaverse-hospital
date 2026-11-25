# Anaverse Hospital — Website & Hospital Information System (UI)

![Bilingual](https://img.shields.io/badge/Bilingual-DE%20%7C%20AR-1565C0) ![Static](https://img.shields.io/badge/Static-HTML-E34F26?logo=html5&logoColor=white)

> Hospital website in German and Arabic, plus the interface of a hospital information system with one view per department.

## Overview
A production project built and deployed by **Mahmoud Hasan**. This repository holds the source code only. The client's secrets,
databases, uploaded files and personal data are not included; where the code needs them, they are replaced with placeholders.

**Tech stack:** HTML5 · CSS3 · Vanilla JS

## Features
- Hospital website in German and Arabic with a language switch
- One dashboard per department: doctor, emergency, lab, nursing, pharmacy, patient relations
- Patient lists, lab results, staff chat and alerts (demo data)
- Shared design system; each department has its own colour

## Project structure
```
index.html          hospital website
system/index.html   system overview
system/doctor.html  emergency.html  lab.html  nursing.html  pharmacy.html  relations.html
```

## Getting started
Static files: open `index.html` or `system/index.html`. All doctor and patient names are fictional demo data.

## Security & privacy
- No credentials in the repository. API keys, passwords and database settings are placeholders (`CHANGE_ME`, `YOUR_…`, `your_db_password`).
- Runtime data (customers, messages, appointments, logs, uploads) is left out.
- Personal names, phone numbers and addresses in the default content are replaced with sample data (e.g. Max Mustermann, +49 151 00000000, Musterstraße 1).

## Author
**Mahmoud Hasan** · [GitHub](https://github.com/MahmoudHasan2)
