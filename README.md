# Weight Tracker App – Reflection

### App Summary  
This app is a Weight Tracker that lets users log their daily weight, set a personal weight goal, and receive a notification when they reach that goal. The main purpose is to support users who want to monitor their progress in a simple and consistent way, without complicated graphs or cluttered screens.

### User-Centered Design  
The app has three main screens:
- **Home:** Add weight entries and view progress history.
- **Goal:** Set or update a weight goal.
- **Notifications:** Enable or disable goal notifications.

The UI was kept clean and easy to follow. Each screen focuses on one main task so users don’t get overwhelmed. Buttons and input fields are clearly labeled, and the layout has space and consistency, making it user-friendly.

### Coding Strategy  
I built the app in small steps. First, I connected the UI to the logic. Then I set up the local database using SQLite to store user data. I used RecyclerView to display past weight entries because it’s efficient and easy to update. Breaking work into smaller parts helped me stay organized and made bugs easier to find and fix. I would use this same strategy again in future projects.

### Testing and Debugging  
I tested as I developed by running the app in the emulator and checking values in the database. I also used log messages to verify data changes. Testing regularly helped me catch issues early, like saving incorrect values or screens not updating. This made the final app more stable.

### Overcoming Challenges  
The biggest challenge was managing notifications and ensuring settings stayed consistent even when switching screens. I had to adjust how the app saved notification preference state so it wouldn’t reset. Working through this helped me understand permissions and app state better.

### Strengths and Success  
The database and data display features are especially strong in this app. The app reliably stores data, updates the UI smoothly, and keeps interaction simple. This shows solid understanding of SQLite, RecyclerView, and user-focused design. The final app works well and supports the original goal of helping users track progress in a positive, simple way.
