# Url-Shortener
Project is analog of https://goo.gl/. It simplifies url-links (for example: https://seattle.craigslist.org/d/software-qa-dba-etc/search/sof -> goo.gl/M66xUC).

##### Features: 
1. Input field and button “Shorten URL”.
2. Checking input.
3. Autoremoving unused strings from DB by schedule (3 days).
5. Countering of clicks by URL.
6. History of transformations (list).
7. Sending e-mail with new shorten URL.

##### Technologies: 
* Java.
* AWS (S3, Route 53, API Gateway, Lambda, DynamoDB).
* HTML, CSS, JavaScript, Bootstrap.

