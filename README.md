# GramBazzar
🛒 GramBazaar Quick Commerce

GramBazaar is a fully responsive, frontend-only quick commerce web application designed to simulate a modern 10-minute delivery platform (like Blinkit, Zepto, or Instamart).

It features a fully functional cart, dynamic AI-generated product images, a WhatsApp-based checkout system, simulated live GPS tracking, and an integrated AI Shopping Assistant.

✨ Features

⚡ Quick-Commerce UI/UX: High-contrast, vibrant design with sticky headers, floating carts, and smooth drawer animations.

🤖 Grama AI Assistant: An integrated generative AI assistant (powered by Gemini) that acts as a customer care executive. It knows your inventory and can speak in multiple regional languages (Marathi, Hindi, English, etc.).

📱 WhatsApp Checkout: Users compile their cart and are instantly redirected to WhatsApp with a neatly formatted receipt to process the order.

📍 Live GPS Simulation: After checkout, a beautifully animated modal simulates a delivery partner navigating to the user's location.

🎨 AI-Generated Imagery: Uses Pollinations AI to dynamically generate unique, realistic packaging photos for products based on their name and brand.

🛒 Advanced Cart Logic: Stepper buttons (- 1 +) sync perfectly across product cards, the slide-out drawer, and the floating cart summary.

🎙️ Voice Search: Hands-free product searching using the native Web Speech API.

🛠️ Tech Stack

HTML5: Semantic structure.

Tailwind CSS (via CDN): Rapid, responsive, and modern styling.

Vanilla JavaScript: State management, cart logic, DOM manipulation, and API fetching.

Gemini API: Powers the Grama AI conversational assistant.

Pollinations AI: Generates dynamic product images.

🚀 How to Run and Deploy on GitHub

Because this application is 100% client-side (no Node.js backend or database setup required), you can host it entirely for free on GitHub Pages.

Step 1: Create your Repository

Log in to your GitHub account.

Click the + icon in the top right and select New repository.

Name your repository (e.g., grambazaar-quick-commerce).

Make it Public and click Create repository.

Step 2: Upload the Code

In your new repository, click on uploading an existing file.

Upload the index.html file (which contains all the HTML, CSS, and JS).

Upload this README.md file.

Click Commit changes.

Step 3: Deploy to GitHub Pages (Free Hosting)

In your repository, click on the Settings tab (the gear icon near the top).

On the left sidebar, scroll down and click on Pages.

Under the Build and deployment section, look for Source.

In the dropdown under "Branch", select main (or master) and leave the folder as /(root).

Click Save.

🎉 You're done!
GitHub will take a minute or two to build your site. Once finished, it will display a URL at the top of the Pages settings (e.g., https://yourusername.github.io/grambazaar-quick-commerce/). Click it to view your live, globally accessible web app!

📝 Configuration

AI Assistant API Key:
The Gemini AI assistant in this code is currently configured to run smoothly in a simulated collaborative environment. If you host this externally and want the AI to function, you will need to replace the apiKey variable in the index.html <script> tag with your own free Gemini API key from Google AI Studio.
