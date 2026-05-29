# my-website

Welcome to my-website — a small, friendly static site that demonstrates a clean homepage and a contact page with a fully featured form. It's intended as a lightweight demo you can use as a starting point for personal sites, small projects, or learning HTML form handling.

## Tone

This repo keeps things informal and approachable while staying polished and professional. Expect short, readable markup and plain HTML that is easy to adapt.

## What you'll find

- [index.html](index.html) — a simple home page with navigation.
- [contact.html](contact.html) — the contact page; includes a complete form for collecting user details and messages.

## Contact form (quick overview)

- Action endpoint: `submit_form.php` (referenced in `contact.html`).
- Method: `POST`
- Fields included:
  - `fullname` (text, required)
  - `email` (email, required)
  - `password` (password, required)
  - `gender` (radio, required)
  - `hobbies[]` (checkboxes)
  - `subject` (select, required)
  - `message` (textarea, required)

## How to use

1. Open [index.html](index.html) or [contact.html](contact.html) directly in your browser for a local preview.
2. To test form submission server-side, add a `submit_form.php` or change the `form` action to a service you control.

## Development notes

- Files are plain HTML — no build step required.
- Feel free to add CSS, client-side validation, or a small backend handler. If you'd like, I can add a minimal `submit_form.php` example or a bit of styling to the form.


"# my-site" 
"# my-website" 
