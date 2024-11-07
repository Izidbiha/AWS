This beginner-friendly project will guide you through setting up a personal website using Amazon S3 and connecting it with a custom domain through Amazon Route 53.

Step #1: Design Your Website
Design your own personal website or download an existing template.
You can find free templates at free-css.com.
for me, I just dowload my resume as a html zipped file and I get my index file and images.

Step #2: Set Up Amazon S3 Bucket
Go to the AWS Management Console and open the Amazon S3 console.
Click "Create bucket" and enter a unique name for your bucket.
In the "Properties" section, enable "Static website hosting."
Upload your website files to the bucket. I uploaded the index file and the images
Set the bucket permissions to allow public access.


Step #3: Purchase a Custom Domain through Amazon Route 53
Optional.. your resume will be hosted on s3 URL but you can purchase a custom domain name and redirect the URL to it.
Open the Amazon Route 53 console.
Choose "Domain registration" and then "Register domain."
Follow the prompts to purchase your custom domain.
In the "Route 53 hosted zones," create a new record set.
Enter your S3 bucket's endpoint as the alias target.