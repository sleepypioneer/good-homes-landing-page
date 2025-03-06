# Good Homes Landing Page

This repository contains the source code for the Good Homes landing page. The landing page is designed to be static, responsive, and accessibility compliant. It provides key information about the Good Homes app, which connects renters and buyers with energy and cost-efficient homes.

## Key Features

- **Logo and Branding**: The landing page prominently displays the Good Homes logo and brand name, along with the tagline "Find tomorrow’s homes today."
- **Illustration**: A stylized illustration of homes is included to visually represent the app's purpose.
- **Message**: A brief description of the app's purpose is provided: "We connect renters and buyers with energy and cost-efficient homes. Let your home take care of you, so you can take care of them."
- **Website URL**: The website URL "www.good-homes.com" is displayed at the bottom of the page.

## Setting Up and Running Pelican Locally

To set up and run Pelican locally, follow these steps:

1. **Create a virtual environment**:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

2. **Install Pelican**:
   ```sh
   pip install pelican
   ```

3. **Clone the repository**:
   ```sh
   git clone https://github.com/sleepypioneer/good-homes-landing-page.git
   cd good-homes-landing-page
   ```

4. **Run Pelican to generate the site**:
   ```sh
   pelican content -o output -s pelicanconf.py
   ```

5. **Serve the site locally**:
   ```sh
   cd output
   python -m http.server
   ```

## Deploying the Site to GitHub Pages

To deploy the site to GitHub Pages, follow these steps:

1. **Push your changes to the main branch**:
   ```sh
   git add .
   git commit -m "Update site"
   git push origin main
   ```

2. **GitHub Actions will automatically build and deploy the site**.

## Virtual Environment Setup

To set up a virtual environment, follow these steps:

1. **Create a virtual environment**:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

2. **Install the required packages**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Run Pelican within the virtual environment**:
   ```sh
   pelican content -o output -s pelicanconf.py
   ```
