Build Status
hng
Installation Guide
You need a server, download Wamp or Xampp
Clone this repository into htdocs of www folder in your respective servers.
If you have not been added to the organization, kindly work in your forked repository and open a pull request here
Fork the repository and push to your staging branch
Merge to your master and compare forks with the original repository
Open a Pull Request.
Read this or watch this for more help
git clone https://github.com/hnginternship5/hng.tech.git
cd hng.tech
cp .env.example .env
php -S localhost:8000
Visit localhost:8000 in your browser
Contribution Guide
git checkout staging
The template for your profile page can be found here views/interns/template.php

Copy the contents of that file
Create a new file with your slack username, e.g mark.php
Paste the contents there
Now your page should be assesible via localhost:8000/interns/mark hng profile
Edit the contents of the file to your profile details
Push to staging branch and open a pull request
Wait for review
Ensure you read this doc here for complete instructions
Failure to do this will warant closing your pull request
