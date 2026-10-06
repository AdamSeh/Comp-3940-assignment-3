Comp 3940 Asignment 3

1. How to compile
   Ppen command prompt or terminal in the projetc/assignment folder.
   Type: javac *.java

2. How to run the server
   While still int he terminal.
   Type: java UploadServer
   The server will start listening on port 8082

3. How to test with browser
   Open a browser and go to: http://localhost:8082/
   - Fill out the caption, date, and select a file (image or text).
   - Press Submit to see the aimages uploaded int he projects image folder

4. running the client app:
   java UploadClient
   (Programmatically executes a multipart POST request containing caption, date, and file payload).

5. Design patterns used:
   - Multi-threading (UploadServerThread handles each client connection concurrently)

   - Custom Exception (FileUploadException)
      I use this in the UploadServlet.java file

6. Things I could not do
   - I was not able to make it so that the list of links in the page actually take you to the image.