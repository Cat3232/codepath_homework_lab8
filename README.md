

Time spent: **18** hours spent in total

# Project 7 - WordPress Pen Testing

Time spent: **18** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pen Testing Report

### 1. (Required) Vulnerability Name or ID

- [ ] Summary: This attack requires admin access.
  - Vulnerability types: xss injection
  - Tested in version: 4.2
  - Fixed in version: 5.0
- [ ] GIF Walkthrough: 
<img src="Lab 8 q 1.gif" alt="Question 1">
- [ ] Steps to recreate: This doesn't require HTML and only requires an imbedded link with xss injected.
- [ ] Affected source code: imbedded link
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  
### 2. (Required) Vulnerability Name or ID

- [ ] Summary: This attack requires admin access.
  - Vulnerability types: xss injection
  - Tested in version: 4.2
  - Fixed in version: 6.4
- [ ] GIF Walkthrough: 
<img src="Lab 8 q 2.gif" alt="Question 2">
- [ ] Steps to recreate: You'll need to access the html on the page and inject the code anywhere you want. Once the victim opens the page the XSS will run.
- [ ] Affected source code: HTML
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

### 3. (Required) Vulnerability Name or ID

- [ ] Summary: This attack requires admin access.
  - Vulnerability types: xss injection
  - Tested in version: 4.2
  - Fixed in version: 7.8
- [ ] GIF Walkthrough: 
<img src="Lab 8 q 3.gif" alt="Question 3">
- [ ] Steps to recreate: You'll need to access the html on the page and inject the code. Once the vicim opens the web page the xss will run.
- [ ] Affected source code: HTML
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with  ...
<!-- Recommended GIF Tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while doing the work

Had a hard time getting word press up and running on my windows computer.
