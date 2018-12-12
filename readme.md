# Speeding Up Google Fonts

This is one of the repos I used for testing out different strategies for using Google Fonts on a website. I tested each one using webpagetest.org using the easy setting.

## Tests

### No preconnect vs preconnect

**Without preconnect**
Code: https://jsbin.com/xacifi/2/edit?html,css,output
Deployed website: https://output.jsbin.com/xacifi/2 
Test results: 

**With preconnect**
Code: https://jsbin.com/kegerux/2/edit?html,output
Deployed website: https://output.jsbin.com/kegerux/2
Test results: 

### Preconnect vs self-hosting and preloading

**With preconnect**
Repo: https://github.com/siakaramalegos/google-fonts-preconnect 
Deployed website: https://angry-snyder-f34116.netlify.com/
Test results: https://www.webpagetest.org/result/181212_0B_6134652d0ad5e16e8ac00b14775bd536/ 

**Self-hosting and preloading**
Repo: https://github.com/siakaramalegos/google-fonts-self-hosting
Deployed website: https://elastic-snyder-7a396e.netlify.com/
Test results: 