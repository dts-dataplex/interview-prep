# Interview Prep Platform

A mobile-friendly interview preparation tool with voice recording, AI-powered feedback, and SWOT analysis.

## Features

- **Voice Recording**: Record your answers using speech-to-text (Chrome required)
- **Back-and-forth Conversation**: The AI interviewer asks follow-up questions until satisfied
- **SWOT Analysis**: Get a detailed breakdown of strengths, weaknesses, opportunities, and threats after each question
- **Customizable Context**: Set the role, company, and interview focus
- **Text-to-Speech**: Listen to questions and feedback read aloud
- **Mobile Optimized**: Works on iPhone and Android in Chrome

## Requirements

- Chrome browser (required for Web Speech API)
- Anthropic API key ([Get one here](https://console.anthropic.com))
- Microphone access

## Deploy to GitHub Pages

1. **Create a new GitHub repository**
   - Go to github.com and create a new repository
   - Name it something like `interview-prep`

2. **Upload the files**
   - Upload `index.html` to the repository root
   - Or use git:
     ```bash
     git init
     git add index.html README.md
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/YOUR_USERNAME/interview-prep.git
     git push -u origin main
     ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click Save

4. **Access your site**
   - Your site will be live at: `https://YOUR_USERNAME.github.io/interview-prep`
   - It may take a few minutes to deploy

## Usage

1. Open the app in Chrome on your phone or computer
2. Enter your Anthropic API key (stored in memory only, never saved)
3. Customize the interview context or use the default
4. Press "Start Interview" to get your first question
5. Press "Start Recording" and speak your answer
6. Press "DONE" when finished (not before!)
7. Receive feedback and follow-up questions
8. When the interviewer is satisfied, view your SWOT analysis
9. Continue to the next question or reset

## Security Note

Your API key is:
- Stored only in browser memory
- Never saved to disk or sent anywhere except Anthropic's API
- Cleared when you close the browser tab

## Troubleshooting

**Microphone not working?**
- Ensure you're using Chrome
- Check that microphone permissions are enabled for the site
- On iOS, you may need to grant permission in Settings → Safari → Microphone

**API errors?**
- Verify your API key is correct
- Check that you have available credits at console.anthropic.com
- Ensure you have a stable internet connection

## License

MIT
