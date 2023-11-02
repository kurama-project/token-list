# Update Token and Automatically Deploy to Netlify

1. **Add Token Configuration and Icon:**

   - Open the `tokens/kurama.json` file in your project.
   - Add the token configuration following the required format.
   - Ensure the icon for the token is placed in the `lists/images` directory.
   - Make sure the icon file's name matches the token's name specified in the configuration.

2. **Generate the List:**

   - Open your terminal and navigate to the project directory.
   - Run the following command to generate the list. Ensure that the project provides the `npm run makelist` command:

     ```bash
     npm run makelist
     ```

3. **Commit Changes to Git:**

   - Use Git commands to commit your changes to the Git repository:

     ```bash
     git add .
     git commit -m "Add token configuration and icon"
     git push
     ```

4. **Auto-Deploy to Netlify:**

   - Once you've pushed your changes to the Git repository, the project is configured to automatically deploy to Netlify.
   - You can access the updated token list at the following URL: [https://tokenlist.kurama.app/kurama.json](https://tokenlist.kurama.app/kurama.json).

Please ensure you follow these steps carefully to update the project and trigger automatic deployment to Netlify.

