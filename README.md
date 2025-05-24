# ContentFlow

**ContentFlow Gamified v2 is a web-based, single-page application designed to streamline and gamify your content creation process. It provides a structured workflow, AI-powered assistance, and engaging gamification elements to help you consistently produce high-quality content.**

![ContentFlow Screenshot](placeholder_screenshot.png)
*(Suggestion: Replace `placeholder_screenshot.png` with an actual screenshot of the application)*

## ✨ Key Features

*   **Structured Workflow Management:**
    *   Organize content creation into predefined steps: Research, Define, Grid Update, Script, Produce, Edit, Publish, Monitor.
    *   Track the status of each step and the overall progress of your content pieces.
    *   Define AI context (Topic, Audience, Platform, Objective) for tailored assistance.
*   **🚀 Gamification Engine:**
    *   Earn points for completing tasks and content pieces.
    *   Level up based on your accumulated points.
    *   Maintain a daily activity streak.
    *   Unlock achievements for various milestones.
    *   Visualize your stats on a personal dashboard and sidebar.
*   **🤖 AI-Powered Assistance (Google Gemini):**
    *   Integrate your Google AI (Gemini) API key to unlock powerful assistance.
    *   Generate content ideas, suggest formats, refine objectives.
    *   Create hooks, outlines for carousels/videos, improve script clarity.
    *   Get suggestions for visuals, shot lists, design styles, and tech tips.
    *   Generate titles, captions, hashtags, and CTAs.
    *   Check readability and identify KPIs.
    *   **NEW:** Enhance 'Topic', 'Audience', and 'Objective' fields with specialized AI prompts for Business Intelligence contexts.
    *   **NEW:** Generate content grid ideas (Date, Topic, Format, Platform, etc.) and export them as an `.xlsx` file.
*   **📊 Dashboard Overview:**
    *   Quickly access actions like starting new content or viewing your library.
    *   See your current streak, in-progress content, and recent achievements.
*   **📚 Content Library:**
    *   View all your created content pieces.
    *   Search by title and filter by status (Pending, In Progress, Completed).
    *   Easily navigate to or delete content pieces.
*   **⚙️ Settings & Customization:**
    *   Manage your Google AI API Key (stored in browser `localStorage` - **use with caution**).
    *   Switch between **Dark** (default) and **Light** themes.
*   **💾 Local Data Persistence:**
    *   All your data (stats, content, API key, theme) is saved in your browser's `localStorage`.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+)
*   **Styling:** Tailwind CSS
*   **Icons:** Lucide Icons
*   **Spreadsheet Export:** SheetJS (`xlsx.full.min.js`)
*   **AI Integration:** Google Gemini API (requires user's own API key)

## 🚀 Getting Started

ContentFlow is a client-side application and can be run directly in your web browser.

1.  **Clone the repository (or download the files):**
    ```bash
    git clone https://github.com/your-username/contentflow.git
    cd contentflow
    ```
2.  **Open `ContentFlow.html` in your web browser:**
    *   Simply double-click the `ContentFlow.html` file, or right-click and choose "Open with" your preferred browser.

3.  **Set up your AI API Key (Optional, for AI features):**
    *   Click on the "Ajustes" (Settings) icon in the sidebar.
    *   Enter your Google AI (Gemini) API Key in the designated field.
    *   Click "Guardar API Key".
    *   **Security Warning:** Your API Key is stored in `localStorage`, which is not secure for sensitive keys. Use with caution, preferably with restricted or temporary keys.

## 📖 How to Use

1.  **Navigate Views:** Use the sidebar to switch between Dashboard, Workflow Activo, Biblioteca Contenido, and Logros y Stats.
2.  **Start New Content:**
    *   From the Dashboard, click "Iniciar Nuevo Contenido".
    *   Enter a title for your content piece.
3.  **Work through the Workflow:**
    *   The new content piece will open in the "Workflow Activo" view.
    *   Fill in the "Contexto General (Para IA)" fields (Topic, Audience, Platform, Objective, Notes) to guide AI suggestions.
    *   For each step:
        *   Complete the required tasks for that stage of content creation.
        *   Use the "Asistencia IA ✨" buttons to get AI-powered help.
            *   For the "Actualizar Grilla" step, you can specify the number of rows and click "Generar Ideas para Grilla". Then, download the generated ideas as an `.xlsx` file using the "Descargar Grilla" button.
        *   Mark the step as complete by checking the checkbox on the right.
4.  **Track Progress:**
    *   Your points, level, and streak will update automatically as you complete tasks.
    *   Check the Dashboard and Logros y Stats view for your progress and unlocked achievements.
5.  **Manage Content:**
    *   Visit the "Biblioteca Contenido" to see all your projects, search, filter, and revisit or delete them.
6.  **Customize:**
    *   Go to "Ajustes" (Settings) to toggle between Dark and Light themes.

## ⚠️ AI Integration & API Key

*   The AI features are powered by the Google Gemini API.
*   You **must** provide your own API key in the Settings to use these features.
*   The application makes direct calls from your browser to the Gemini API.
*   **Important Security Note:** Storing API keys in browser `localStorage` is **not secure** and can be accessed by browser extensions or XSS attacks. This application is intended for personal use or with API keys that have limited permissions and a short lifecycle. **Use this feature at your own risk.**

## 🎮 Gamification

*   **Points:** Earned for completing steps and entire content pieces.
*   **Levels:** Progress through levels as you accumulate points.
*   **Streaks:** Maintain a daily streak by completing at least one task.
*   **Achievements:** Unlock various achievements for different milestones.
*   **Visual Feedback:** Toasts for achievements and level-ups, plus dynamic stat displays.

## 🎨 Theme Customization

*   Easily switch between a sleek **Dark Mode** (default) and a clean **Light Mode** via the Settings panel. The application will remember your preference.

## 💾 Data Storage

*   All your data, including content pieces, user statistics, achievements, API key, and theme preference, is stored locally in your web browser's `localStorage`.
*   This means your data is persistent on the browser you use it on, but it won't sync across different browsers or devices.
*   Clearing your browser's `localStorage` for this site will erase all your data.

## 🌱 Future Enhancements

*   User authentication and cloud data storage for cross-device access.
*   More advanced AI features and model integrations.
*   Customizable workflow templates.
*   Calendar integration for content scheduling.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Please feel free to check the [issues page](https://github.com/your-username/contentflow/issues).

*(If you plan to accept contributions, you might want to add a `CONTRIBUTING.md` file with more detailed guidelines.)*

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

*(Suggestion: Create a `LICENSE.md` file with the MIT License text if you intend to use it.)*

---

Enjoy creating content with ContentFlow!
