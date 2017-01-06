# gif library
This project was guided by Team Treehouse, under the Java Web Development Track. The purpose of this project was to launch an embedded Java Web Application, using Spring, with database connectivity using Hibernate and H2.

This project is not 100% complete, and was used for Java Web Design Practice. This is meant to represent a GIF image library, similar to giphy.com

- Uses Gradle Dependency Management
- Adds persisted data, using an H2 database
- Manages data with Hibernate

What this app does:

- Serves dynamic web content according to URI, including index and detail pages for categories and GIFs
- Includes database connectivity, where GIF data is stored
- Allows a user to perform CRUD (create, read, update, delete) operations on GIF and category data
- Performs server-side form validation for adding/updating GIFs and categories
- Serves static assets, such as images, fonts, CSS, and JS

In the works:

- Implement user authentication

Setup:

For Developers:
- First, open src/main/resources/app.properties
- Within this file, edit the giflib.db.url line to match your project directory.
- You may also edit the login username and password for your data base on the next lines if you wish.
- Open your project in terminal/command line
- Use the following command: java -cp h2-1.4.190.jar org.h2.tools.Server
- This should open a browser window, displaying the h2 login screen. Copy and paste the giflib.db.url mentioned above, into the URL field
- Use the username and password you specified earlier. Test connection, and sign in.
- Within your IDE (I used InteliJ for this project), open the gradle toolbar, and run tasks/application/bootRun
- After the bootRun task is complete, open a browser and enter localhost:8080
- You should now see the Java Web Application displayed.
- Navigate back to your h2 database page and refresh, all data tables should now be present.

For non-developers

- Once some more work is done on this, I may deploy this for anyone to use online. For now, watch the following video for a demonstration: https://youtu.be/jdOKVHo9zEU


Video Demonstration:
https://youtu.be/jdOKVHo9zEU
