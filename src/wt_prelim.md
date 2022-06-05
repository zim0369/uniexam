# Questions

**Questions from SKN's recent(May 2022) prelim examinations**

**1. Write benefits of using PHP and mysql. Explain PHP module to insert a
record in MySQL database.**

*   Major Advantages of PHP and MySQL Development:

    *   Cost-effective personalized PHP applications solutions;

    *   A complete open-source platform;

    *   Frequently updated (these updates are also available for free);

    *   Availability of various add-ons and plugins;

    *   Superior website performance;

    *   Vast amount of database interfaces;

    *   PHP checks various levels of security;

    *   Integration facility with various other open-source platforms;

    *   Integrates other software languages such as C, C++, JAVA/AJAX, etc;

    *   Supports Joomla, Drupal and WordPress CMS, and osCommerce and Zen Cart
        shopping carts;

    *   HTML Code can be embedded within PHP Code;

    *   Cross-platform ability;

    *   Server-side web programming language;

    *   Large user community.

    *   PHP uses **mysqli\_query** function to insert records in table. This
        function takes three parameters and returns TRUE on success or FALSE on
        failure.

    *   The mysqli\_query() function accepts a string value representing a query
        as one of the parameters and, executes/performs the given query on the
        database.

    *   Syntax:

    <!---->

        mysqli_query($con, query)

**2. What is the use of the XmlHttpRequest object? Explain its use with the help
of simple javascript code.**

*   XMLHttpRequest (XHR) objects are used to interact with servers. You can
    retrieve data from a URL without having to do a full page refresh. This
    enables a Web page to update just part of a page without disrupting what the
    user is doing. XMLHttpRequest is used heavily in AJAX programming.

*   XMLHttpRequest Example: When you type a character in the input field below,
    an XMLHttpRequest is sent to the server, and some name suggestions are
    returned (from the server):

    ![xhr example](pictures/xhr_example.png)

*   Code:

    ```js
        // Create an xhr object
      var xhttp = new XMLHttpRequest();
        // specify the function to execute when xhr object's status changes
      xhttp.onreadystatechange = function() {
        // When readyState is 4 and status is 200 then response is ready
          if (this.readyState == 4 && this.status == 200) {
        // The responseText property returns the server response as a text string
             document.getElementById("demo").innerHTML = xhttp.responseText;
          }
      };
      xhttp.open("GET", "filename", true);
      xhttp.send();
    ```

<!-- CODE -->

**3. Draw and explain how AJAX works with the help of suitable examples.**

*   AJAX = Asynchronous JavaScript and XML.
*   AJAX is a technique for creating fast and dynamic web pages.
*   AJAX allows web pages to be updated asynchronously by exchanging small
    amounts of data with the server behind the scenes. This means that it is
    possible to update parts of a web page, without reloading the whole page.
*   How AJAX works:

    ![ajax working](pictures/ajax_working.gif)
*   Example:
    *   AJAX was made popular in 2005 by Google, with Google Suggest.
    *   Google Suggest is using AJAX to create a very dynamic web interface: When you start typing in Google's search box, a JavaScript sends the letters off to a server and the server returns a list of suggestions.

**4. Write a program of your choice that demonstrates use of properties of DOM.
Also list the limitations of using XML.**

**5. How to use interceptors in strut 2? List and describe important
interceptors provided by strut 2 framework.**

**6. What are the web services? List and explain types and components of web
services.**

**7. What different configuration files are required to develop any struts
application?**

**8. What are enterprise java beans? Draw and explain main components of EJB
architecture.**

**9. Explain what is Angular Expression? Explain what is the key difference
between angular expressions and JavaScript expressions?**

**10. Write a PHP script to display the squares and Cubes of 1 to 10 numbers.**

**11. What is an association array in PHP? Explain it with the help of simple
PHP code.**

**12. Explain various directives in AngularJS & Create simple angular JS
application to display, "Hello, Input Name" using proper directive.**

**13. What is EJB? Explain types of EJB? Also explain uses of Ruby.**

**14. Draw and explain the role of EJB container in enterprise application.**

**15. Explain how Rails implements AJAX? Mention what are the positive aspects
of Rails.**

**16. Explain how you define instance variable, global variable and class
variable in Ruby? Explain what is rake in Rails.**
