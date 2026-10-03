# Beyond the Worksheet: AI Prompt Builder

A one-page tool that helps science teachers write a prompt for an AI tool (Gemini, Claude, ChatGPT or Copilot), so it builds a working classroom simulation as a single HTML file. It was made for the ISTA 2026 session *Teaching Science in the Age of AI* by Matt Hopkins and Karl Craddock (William Fremd High School, District 211).

## What's on the page

- **Prompt Builder.** Fill in your lab's variables and options, and the prompt writes itself. Answers are saved in your browser.
- **Bring your own lab.** A prompt to paste next to a lab PDF you upload to the AI.
- **Starter prompts.** Five tested prompts (Bio, Chem, Physics, Earth, Physical Science). You can edit any of them before copying.
- **Links** to the Fremd ScienceSims library.

## Hosting

The page is a single self-contained file, `prompt-builder.html`, with no build step.

- **GitHub Pages:** put the file in the repo, then go to **Settings → Pages** and deploy from the `main` branch. The page will be at `https://<user>.github.io/DepartmentalSites/prompt-builder.html`.
- **CodePen:** paste everything between `<body>` and `</body>` into the HTML panel. Put the `<style>` contents in the CSS panel and the `<script>` contents in the JS panel.

## Editing

- **Starter prompts** live in the `<pre class="starter">` blocks. Leave the Schoology sentence off the end, because the page adds it automatically, along with a line tailored to the AI tool the teacher picked.
- **The shared Schoology sentence and the AI-specific lines** are near the top of the script (`SCHOOLOGY`, `AI`).
- **Colors** are CSS variables at the top of the stylesheet: Fremd green and gold, District 211 maroon.

## License

Free to use, free to copy. Change the numbers, change the subject, put your name on it.
