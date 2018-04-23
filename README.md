# Google-Authorization
Google+ Login API


1) Go to Google API Console : https://console.developers.google.com/


2) If you have not created a project, create a project by clicking Create Project (at the top)


3) Go to the project page and click the Library tab on the left, search for Google+ API and enable it. This is required to get user information (This works for users whether or not they have a Google+ profile)


4) Now click on the Credentials tab on the left


5) Click on the button Create Credentials. Choose OAuth client ID in the dropdown.


6) In the next page choose application type as Web application. Add a name.


7) Add a redirect url in the section Authorised redirect URIs. This url should point to the redirect url script. (gauth.php in the attached codes). You can add a localhost url if you want.


8) You can leave out Authorised JavaScript origins as blank. Click on the Create button.


9) On success you will get the App Client ID and App Secret. Save those as they will be required later.


10) In the next page click on the OAuth Consent Screen tab. Add your Email address and Product name there and click on Save.


11) Edit settings.php and add your Client ID, Client Secret and Redirect Url


12) Run index.php in the browser
