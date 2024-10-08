# Static Website Deployment on AWS S3

## Project Overview
This project demonstrates how to deploy a static website using AWS S3, providing practical cloud computing experience. The website consists of four HTML pages and is hosted publicly on S3.

## Features
- Simple static website with four HTML pages.
- Hosted on AWS S3 with public access.
- Easy to set up and modify.

## Learning Objectives
- Understand AWS S3's static website hosting capabilities.
- Learn about cloud infrastructure, S3 bucket permissions, and static file hosting.

## Prerequisites
- AWS account.
- Basic knowledge of HTML.
- Familiarity with the AWS Management Console.

## Setup Steps

### Step 1: Create an S3 Bucket
1. Log in to AWS Management Console.
2. Go to **S3** and create a new bucket:
   - **Bucket Name**: `your-bucket-name`
   - **Region**: Choose a nearby region.
   - **Block Public Access**: Disable to allow public access.
3. Enable **static website hosting**.

![S3 Bucket Creation](docs/images/s3-bucket-creation.png)

### Step 2: Create HTML Pages
Use an editor like Visual Studio Code to create the following pages:
- `index.html` (main page)
- `custom.html`, `ashish.html`, `modify.html` (additional pages)

![HTML Pages Example](docs/images/html-pages-example.png)

### Step 3: Upload Pages to S3
1. Upload the HTML files to your S3 bucket.
2. Set public read permissions using **ACL**.

### Step 4: Enable Static Website Hosting
1. In the bucket settings, enable **static website hosting** and set `index.html` as the index document.

![S3 Static Website Configuration](docs/images/s3-static-website-configuration.png)

### Step 5: Access the Website
Access the website using the **website endpoint URL** provided by S3.

![Website Endpoint](docs/images/website-endpoint.png)

## Academic Use
This project is ideal for teaching cloud computing concepts and basic web hosting. Students can add more pages or customize content as part of learning.

## Contribution
We welcome contributions! To contribute, fork this repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
