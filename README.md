# Cast — AI Cover Letter Generator

Cast turns a résumé and a job description into a tailored cover letter, right in your browser.

## What it does

Upload a résumé and a job description, pick a tone, and Cast writes a draft cover letter you can edit, copy, or download.

## How to use it

1. Open cast-cover-letter.html in your browser
2. Click the settings icon and add a free Groq API key from console.groq.com/keys
3. Upload your résumé under "Raw material"
4. Add the job description under "The mold" (upload or paste)
5. Pick a tone under "Finish"
6. Optionally note anything you want mentioned
7. Click "Cast letter"
8. Edit the draft, then copy it or download it as a text file. Click "Recast" to try again

## Files

cast-cover-letter.html — the app
favicon.ico — browser tab icon
cast-icon.png — reference icon

## Notes

Runs entirely client side, no server. Your API key stays in your browser and is only used to call Groq directly. Files are parsed with pdf.js and mammoth.js. Uses Groq's llama 3.3 70b versatile model.
