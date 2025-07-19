🚀 HOW TO DEPLOY THIS TO RENDER.COM (FOR REAL CUSTOMERS)

STEP 1: Sign up at https://render.com (it's free)

STEP 2: Create a new "Web Service"

STEP 3: Choose "Manual Deploy" → "Deploy from a zip or folder"

STEP 4: Use these settings:
   - Runtime: Node
   - Build command: npm install
   - Start command: node server.js

STEP 5: Add these environment variables (from your .env file):
   MPESA_CONSUMER_KEY
   MPESA_CONSUMER_SECRET
   MPESA_SHORTCODE
   MPESA_PASSKEY
   MPESA_CALLBACK_URL

STEP 6: Deploy and you'll get a permanent link like:
   https://your-service-name.onrender.com

✅ Paste that link into your Google Form.
