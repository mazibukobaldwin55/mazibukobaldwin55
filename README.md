# Hi there, I'm Baldwin Mazibuko 👋

## About Me

I'm **Sihle Baldwin Mazibuko**, a final-year BSc Information Technology (Data Science) student at Richfield College in Johannesburg. I'm focused on turning data into practical, working tools. My latest project is a machine learning model that predicts Premier League player market values, with calibrated prediction intervals and a live Streamlit app. I also build Android apps and database-driven desktop systems, and I'm looking to grow in data analytics and machine learning.

## 📂 Projects

### 🔹 Premier League Player Market Value Prediction (2026)

Machine learning model and interactive web app that predicts a Premier League player's end-of-season market value from age, on-pitch output, club success, and last year's valuation, with calibrated prediction intervals.

- Built a **rolling, chronological backtest** (2016-2025) where each season is predicted by a model trained only on earlier seasons, giving 3,911 out-of-sample predictions.
- The final linear model reaches **R² 0.866 on log value** versus 0.662 for a naive "last year's value" baseline, with a median absolute error of about 19%.
- Added **80% split-conformal prediction intervals**, calibrated by age band, that cover 81.7% of out-of-sample players.
- Compared linear models and gradient boosting, and analysed which features drive the prediction using grouped permutation importance.
- Deployed an interactive **Streamlit app** with a player look-up tab (actual vs predicted value with intervals), a what-if tab for changing a player's inputs, and an about tab.
- **Tools:** Python, pandas, NumPy, scikit-learn, matplotlib, Streamlit, Jupyter

🔗 View repository - https://github.com/mazibukobaldwin55/Premier-League-Player-Value-Prediction

🚀 Live app - https://premier-league-player-value-prediction-zxpgkgqtqntxcsfjkywexo.streamlit.app/

### 🔹 Smart Pantry — Android Application (2026)

Native Android app that helps users manage their pantry inventory, track food expiry dates, and reduce household food waste.

- Built inventory management features to track and monitor pantry and kitchen items in real time.
- Implemented expiration tracking with notifications and alerts for items nearing their expiry dates.
- Organised items by storage location (Pantry, Refrigerator, Freezer) and by type (Produce, Dairy, Dry Goods).
- Added search and filtering so users can quickly find items, with a UI designed to Material Design guidelines.
- Structured the app using MVVM / Clean Architecture principles.
- **Tools:** Kotlin, Android Studio, Android Jetpack, Material Components, Gradle (Kotlin DSL)

🔗 View repository - https://github.com/mazibukobaldwin55/SmartPantryManager

### 🔹 Pharmacy Inventory Management System (2026)

Desktop inventory and point-of-sale system for a local pharmacy, built with Java and MySQL. It covers medicine and supplier management, checkout and billing, and sales reporting, with separate interfaces for administrators and cashiers.

- Implemented **role-based authentication** so administrators and cashiers each get their own interface, and cashiers cannot modify medicines, suppliers, or user accounts.
- Built full **CRUD functionality** for medicines, suppliers, and cashier accounts in the administrator dashboard.
- Developed a **cashier point-of-sale** module with a shopping cart, quantity adjustment, and checkout that validates stock availability and expiry status before completing a sale.
- Automated **stock deduction** after each successful sale, and added a stock-check screen where cashiers can search medicines by price, availability, and expiry date.
- Generated **customer bills** (sale number, date, cashier, items, quantities, total) that can be printed or saved as text files.
- Created four **administrator reports**: Sales, Item-Wise Sales, Low Stock (items at or below reorder level), and Medicine Expiry.
- Designed a relational **MySQL schema** with foreign key relationships and sample data, connected to the Java application through JDBC.
- Packaged the application as a **standalone Windows executable** that bundles the Java runtime.
- **Tools:** Java, Swing/AWT, JDBC, MySQL, IntelliJ IDEA, MySQL Workbench

🔗 View repository - https://github.com/mazibukobaldwin55/Pharma-Inventory-Management-System

## 🎓 Certifications

- **Microsoft Azure Fundamentals (AZ-900)** — Microsoft, via Coursera (2026). Covers core Azure services, cloud pricing models, security, and compliance, with practical understanding of Azure compute, storage, networking, and identity services.

  ## 🛠️ Skills

- **Languages:** Python, SQL, Java, Kotlin
- **Data analysis:** pandas, NumPy, data cleaning and merging, feature engineering, exploratory analysis, visualization with matplotlib and seaborn
- **Machine learning:** scikit-learn (pipelines, imputation, encoding, linear models, gradient boosting), walk-forward backtesting for time-ordered data, model evaluation (R², error analysis), permutation feature importance
- **Statistics:** regression modelling, log transformations, conformal prediction intervals and coverage calibration
- **Deployment:** Streamlit apps, model persistence with joblib, Streamlit Community Cloud
- **Mobile:** Android app development (Android Studio, Jetpack, Material Design), MVVM / Clean Architecture
- **Desktop:** Java Swing/AWT GUI development
- **Databases:** MySQL, JDBC, relational database design
- **Cloud:** Microsoft Azure (AZ-900 certified), cloud computing fundamentals
- **Tools:** Jupyter, IntelliJ IDEA, Android Studio, MySQL Workbench, Gradle, Git & GitHub

  ## 🌱 Currently Learning

- Python for Data Science
- Data Analysis
- Machine Learning
- SQL
- Data Visualization
- Statistics

## 🎯 Goals

- Build real-world data science projects.
- Contribute to open-source projects.
- Grow my portfolio and expand my knowledge in AI and Machine Learning.
- Collaborate with other developers and data enthusiasts.

## 📫 Connect with Me

📍 Johannesburg, Gauteng · 📧 [mazibukobaldwin55@gmail.com]

Feel free to connect with me and follow my learning journey!

> *"Every expert was once a beginner. Keep learning, keep growing."* 🚀
