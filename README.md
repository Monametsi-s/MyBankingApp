# Horizon Banking Platform - Learning Project

This repository contains my progress and code as I follow a comprehensive YouTube tutorial to build a modern online banking platform called **Horizon**. The goal of this project is to learn and implement various full-stack web development concepts and technologies.

**Based on the Tutorial:** https://www.youtube.com/watch?v=PuOVqP_cjkE&t=9s

**Project Description (from the tutorial):**

This tutorial guides you through building and deploying a fully functional online banking platform with features like connecting to multiple bank accounts, real-time transaction display, money transfers between users, secure authentication, and a user-friendly interface.

**Key Features (as I implement them):**

* Connecting to and displaying transactions from linked bank accounts.
* Implementing money transfers between platform users.
* Secure Server-Side Rendering (SSR) authentication.
* Homepage with account balances, connected cards, transaction lists, and spending categories.
* Transaction history page with filtering capabilities.
* Payment transfer page for sending money to external bank accounts.


**Technologies Used (as covered in the tutorial):**

* **Frontend:**
    * Next.js (with App Router, Server Components, Server Actions, Group Routes, Nested Layouts)
    * React
    * TypeScript
    * React Hook Form
    * Zod (for form validation)
    * Shadcn UI (for UI components)
    * Tailwind CSS (for styling)
    * Charts (for data visualization)

* **Backend & Integrations:**
    * Plaid (for connecting to bank accounts and payment processing)
    * Potentially other backend technologies and services as the tutorial progresses.
* **Monitoring & Security:**
    * Sentry (for error tracking and performance monitoring)

**My Progress:**

* [ ] Setting up the basic Next.js project structure.
* [ ] Implementing the signup and login pages.
* [ ] Integrating Plaid for bank account linking.
* [ ] Displaying user bank account details.
* [ ] Fetching and displaying transaction history.
* [ ] Implementing spending category visualization.
* [ ] Building the transfer funds functionality.
* [ ] Implementing secure authentication.
* [ ] Styling the UI with Tailwind CSS and Shadcn UI.
* [ ] Implementing mobile responsiveness.
* [ ] Setting up error monitoring with Sentry.
* [ ] Deploying the application.


**Getting Started:**

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Monametsi-s/MyBankingApp.git
    cd banking-platform
    ```
2.  **Install dependencies:**
    Make sure Node.js is installed on your system. Then, proceed with the following to initialize Shadcn UI:
    ```bash
    npx shadcn-ui@latest init
    ```
    If you encounter any issues, refer to the official Shadcn UI installation guide for Next.js: 
    https://ui.shadcn.com/docs/installation/next

3.  **Set up environment variables:**
    * Follow the tutorial's instructions to obtain necessary API keys (e.g., Plaid, Sentry).
    * Create a `.env.local` file in the root of your project and add the required environment variables as specified in the tutorial. For example:
        ```
        NEXT_PUBLIC_PLAID_CLIENT_ID=your_plaid_client_id
        PLAID_SECRET_KEY=your_plaid_secret_key
        SENTRY_DSN=your_sentry_dsn
        # ... other environment variables
        ```

4.  **Run the development server:**
    ```bash
    npm run dev  # or yarn dev or pnpm dev
    ```
5.  Open your browser and navigate to `http://localhost:3000`.


**Further Learning:**

This project is based on a larger "ultimate nextjs course" mentioned in the video. You can find more information about that course here: 
`https://youtu.be/Zq5fmkH0T78?si=eOGi37fPfMWXjLeV`

**Contributing:**

As this is primarily a personal learning project following a specific tutorial, I am not actively seeking external contributions at this time. 
However, feel free to fork the repository and adapt it for your own learning purposes.

**License:**

This project is licensed under the MIT License.


**Disclaimer:** This project is for educational purposes only and is based on a publicly available tutorial. 
It is not intended for production use or as a real-world financial application without significant further development and security considerations. 
Always handle sensitive financial data with extreme care and adhere to all relevant regulations.