# Drupal

# Download Drupal 10.0.0
https://www.drupal.org/project/drupal/releases/10.0.0
# Extract Here \drupal_sitename
C:\xampp\htdocs\drupal_sitename
# Create Database db_drupal
# Install Drupal For LocalHost Only
## Choose language(done) 
    - English
## Choose profile(done) 
    - Standard
## Verify requirements(done) 
    - Auto
## Set up database(active) - 
    Database name       -     db_drupal
    Database username   -     root
    root

## Install site 
    - Install
## Configure site
    Site name - My Drupal
    Site email address - mslevapatil@gmail.com
    Username -  mslevapatil
    Password -  Confirm password
    Default country -   India
    Default time zone - Kolkata

# Download theme 
https://www.drupal.org/project/business_responsive_theme

# C:\xampp\htdocs\drupal\themes\business_responsive_theme\business_responsive_theme.libraries.yml
    add css File

.container, .page, .main-content, .region-content, .layout-container, .node__content {
  max-width: 100% !important;
  width: 98%;
  padding-left: 5%;
  padding-right: 5%;
  margin: 0 auto;
  box-sizing: border-box;
}

hello