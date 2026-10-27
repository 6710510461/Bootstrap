# AI Log - Week 6: Bootstrap 5

### 1. AI Prompt Used
"Generate a responsive 3-column product card section and a modal trigger button using Bootstrap 5 classes for a local coffee business."

### 2. What Was Received from AI
The AI generated a standard template with 3 cards using `col-md-4`, a basic modal component, and placeholder image URLs.

### 3. Modifications Made & Why
- **Removed remote placeholder images:** Replaced with clean typography and pricing badges inside the card bodies to reduce loading weight and match the minimalist brand look.
- **Added layout utilities:** Added `h-100` and `d-flex flex-column` on the card elements so that all three cards maintain equal height regardless of text length.
- **Custom CSS Override:** Overrode Bootstrap's default `#0d6efd` primary blue with `#1f4e79` to reflect the university/brand theme.
- **Annotations:** Added inline comments in HTML explaining how grid breakpoints (`col-md-4`) and responsive togglers work.