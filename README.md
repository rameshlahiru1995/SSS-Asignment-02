# SSS-Asignment-02


#########   Blogger Post  - https://technoholicsblog.blogspot.com/2018/05/secure-software-systems-assignment-02.html    ###########

Cross-site Request Forgery protection in web applications via Double Submit Cookies Patterns

Implement a web application that matches following criteria.

● User login. You may use hard coded user credentials for demonstration purpose.

● Upon login, generate session identifier and set a cookie in the browser. At the same time, generate the CSRF token for the session and set a cookie in the browser. The CSRF token value is not stored in the server side.

● Implement a webpage that has a HTML form. The method should be POST and action should be another URL in the website.

● When the HTML form is loaded, run a javascript which reads the CSRF token cookie value in the browser and add a hidden field to the HTML form modifying the DOM.

● When the form is submitted to the action, the CSRF token cookie will be submitted and also in the form body, the CSRF token value will be submitted.

● In the web page that accepts the form submission (the URL of the action), obtain the CSRF token received in the cookie and also in the message body. Compare the two values received and if they match, show success message. If not show error message.
