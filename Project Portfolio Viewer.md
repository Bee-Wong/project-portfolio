# Project Portfolio Viewer
### Requirements
* Customizable skeleton website hosted on S3
* Minimal user interface
* Ability to attach CV, certificates, images and GitHub link
* Option to change backgorund and heading colors


### AWS Services Used
* S3 Bucket: 
> Store website files and assets.
> Hosting a static webpage
* Route 53: 
> Manage domain name and DNS settings.

### Unique Selling Point

* Easy-to-use portfolio builder: Create a professional-looking portfolio with minimal effort.
* Customization options: Personalize your portfolio with color and font choices.
* CV and GitHub integration: Showcase your skills and experience with a direct link to your CV and GitHub.
* Hosting on S3: Ensure reliable and scalable hosting for your portfolio.

### Step by step, from creating HTML file to using AWS services to make the webpage accessable  
##### Step 1. Create HTML and CSS Files
* HTML (index.html):
> Structure your portfolio with sections for title, font color selection, file uploads, and content display.
###### Step 2. Set Up Amazon S3 Bucket
* Create an S3 Bucket:
* Access AWS Management Console.
* Go to S3, create a bucket named after your domain/portfolio.
* Upload Files:
> Upload HTML, CSS, and related files to the S3 bucket.
##### Step 3. Configure S3 Bucket for Website Hosting
* Bucket Properties:
* Enable "Static Website Hosting" in the bucket properties.
* Set Permissions:
> Adjust bucket policies for public access to files.
##### Step 4. Set Up Amazon Route 53
* Register Domain:
> In Route 53, register a new domain or use an existing one.
* Create Hosted Zone:
> Establish a hosted zone for your domain in Route 53.
* DNS Records:
> Create an A record to direct to your S3 bucket's static website hosting endpoint.
##### Step 5. Testing and Validation
* Access Portfolio:
> Use the configured domain name to access your portfolio online.
* Upload and Display Content:
> Test file upload functionality to ensure correct display of images and PDFs.
