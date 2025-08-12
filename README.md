# Virtual-Stock-Market-Trading-App-by-Amol-Sadare

In my journey to master Python with practical, real-world applications, I recently built a desktop-based utility called the Nifty / BankNifty Virtual Trading App by Amol Sadare. This tool simulates live intraday trading for Nifty and BankNifty, giving traders and learners a safe, realistic environment to practice strategies without risking real capital.

The app offers a clean, intuitive GUI built using Python’s Tkinter library. At launch, users see live Nifty and BankNifty prices updated every 30 seconds, displayed just below dedicated “Show Chart” buttons. Clicking these opens the official 5-minute candlestick charts on Yahoo Finance for accurate intraday visuals. From there, users can place virtual buy or sell orders, with the app tracking real-time PnL as prices move, alongside a full trade history log to review past decisions.

One key challenge was sourcing reliable market data. After testing several APIs, I settled on yfinance for its consistency. Implementing smooth live updates without freezing the interface required leveraging Tkinter’s after() method. I initially experimented with Streamlit but faced persistent stability issues, leading me to rebuild the interface in Tkinter for greater control. Packaging the project into a .exe using PyInstaller involved resolving dependency conflicts, but the result was a portable, standalone app.

As a finishing touch, I added a clickable LinkedIn profile button for transparency and branding. This project taught me valuable lessons in GUI programming, API integration, real-time data handling, and software deployment — and it stands as a practical example of how Python can bring financial market simulations to life.
