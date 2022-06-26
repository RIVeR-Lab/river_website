# Installation

## Prerequisites
  * Download the latest version of [Hugo](https://github.com/gohugoio/hugo/releases)
  * Install .deb file  
    * `sudo dpkg -i hugo_extended_<VERSION>_Linux-64bit.deb`  
    * `sudo snap install --classic go`

  * Download repo to installation directory
    * `git clone https://github.com/RIVeR-Lab/river_website.git`

## Build
  * Generate static site output
    * `cd river_website`
    * `hugo` for site build only
    * `hugo server` for webserver with automatic refresh of content on `localhost`


# Content

## Project

## News

## Events

## Publications 

## People

  * Create author files
    * `hugo new content/authors/firstname-lastname`
    * Configuration
      * | Attribute | Description    | Example               |
        |-----------|----------------|-----------------------|
        | title     | Displayed name | title: "Adrian Selva" |
        | authors   | Username, must match folder name and name on publications | authors: <ul><li>"adrian-selva"</li></ul> |
        | role      | Degree status | role: PhD Candidate |
        | organizations | 
      
  

# Production Server Configuration

## Hugo Server

## Nginx

## Github Workflow

## HTTPS/Firewall configuration
