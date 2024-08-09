## NPM Packages:
- inquirer.js: Allow us to get input from the user.
- qr-image: To turn the user entered URL into a QR code image as png format.



**Install Dependencies:**
   First, make sure you have Node.js installed. You can check its version using:
   ```
   node -v
   ```

   Next, install the necessary packages:
   ```
   npm install inquirer qr-image
   ```

**Configure package.json:**
   To use ES modules (import/export syntax), update your `package.json` file:
   ```json
   {
       "type": "module"
   }
   ```

**Initialize Your Project:**
   If you haven't already, create a `package.json` file using:
   ```
   npm init -y
   ```

**Run Your Code:**
   Make sure you're in the correct directory and run your script:
   ```
   node index.js
   ```


