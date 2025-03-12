


# Portfolio - Nila

This is my personal portfolio project, showcasing my skills, projects, and certifications. It is built with HTML, CSS, and JavaScript, and deployed using Firebase Hosting.

## Repository
- [GitHub Link](https://github.com/nilavanan-ver-4/portfilo-2003.git)

## Live Demo
- Deployed on Firebase Hosting (URL provided after deployment).

## Technologies
- **HTML**: Page structure
- **CSS**: Styling
- **JavaScript**: Basic interactivity

## Previous Steps Completed
The following steps have already been executed to set up the project:
1. **Install Firebase CLI**
   ```bash
   npm install -g firebase-tools
   ```
2. **Login to Firebase**
   ```bash
   firebase login
   ```
3. **List Firebase Projects**
   ```bash
   firebase projects:list
   ```
4. **Initialize Project with Firebase Hosting Script**
   ```bash
   npx https://gist.github.com/mbleigh/9c8680cf319ace2f506f57380da66e7d portfilo-nila
   ```
   - This likely set up the initial Firebase configuration for `portfilo-nila`.

## Next Steps to Deploy
To deploy this portfolio to Firebase Hosting, follow these steps from your project directory:
1. **Navigate to Project Directory**
   ```bash
   cd portfilo-nila
   ```
   - Ensure you’re in the correct folder containing your project files.

2. **Deploy to Firebase**
   ```bash
   firebase deploy
   ```
   - This uploads your project to Firebase Hosting.
   - After deployment, Firebase will provide a hosting URL (e.g., `https://portfilo-nila.web.app`).

3. **Verify Deployment**
   - Visit the provided URL to ensure the portfolio is live.

## Notes
- If the `npx` script didn’t fully configure Firebase Hosting, run `firebase init hosting` and:
  - Select your Firebase project.
  - Set the public directory to `.` (or the folder with `index.html`).
  - Choose `No` for single-page app unless applicable.
- Ensure your local project matches the GitHub repo before deploying.

