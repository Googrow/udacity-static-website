Deploy Static Website on AWS

In this project, I've deployed a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.


================
in web distribution
	- I've restricted bucket access to force users always access the website endpoint using CloudFront URLs, not Amazon S3 URLs.
	- also forced redirect from http to https
================
website endpoint: https://de9sksvnaqnde.cloudfront.net/index.html
