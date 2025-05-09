**Introduction**

Hello there! Thank you very much for deciding to plunge into our small assignment. We promise it will be an interesting and educational experience!

**How to do**

1. Create a SSH key that uses ED25519
   - Open a terminal
   - Enter this command by replacing "your_email_address" by your email adddress:
       ssh-keygen -t ed25519 -C "your_email_address"
   - You can enter a passphrase if you like

2. Create an account in pico.sh
   - Enter this command in your terminal:
       ssh signup@pico.sh
   - In the "signup" prompt, enter your username (for example your first name)
   - You can create a token (recommended) or explore the service
  
3. Copy the page  https://www.karl.berlin/simplicity.html in your local machine
   - Enter these commands in your terminal:
       mkdir pico-pages && cd pico-pages
       wget https://www.karl.berlin/simplicity.html

4. Create a new Pages project and upload the page
     - Update the page by entering this command (replace "page_name" by the project name you like):
         rsync -rv . pgs.sh:/page_name/
     - Connect to "https://username-page_name.pgs.sh/simplicity.html", replacing "username" and "page_name" by what you have chosen
  
**You're done, well done!**
