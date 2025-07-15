# Easycode1_html


Top 10 Uses of HTML in the Real World
HTML (Hyper Text Markup Language) - is the backbone of the web- a powerful yet simple language that forms the structure of nearly every website we use today. While it's often associated with basic web page creation, HTML's capabilities extend far beyond that.

With the arrival of HTML 5, it has evolved into a versatile tool, supporting everything from responsive web design and offline application to game development and data storage.

We would have frequently heard of the advantages of HTML describing it to be platform-independent (works on all operating systems like windows, Linux, etc), easy to learn, no setup (simply saving the document with the extension .html and opening it in the browser runs the HTML code) and installations, etc.

Uses of HTML
The scope of HTML according to us is always limited to the creation of webpages using HTML, however, there are a lot more. Here, in this article, we have analyzed the various applications of HTML, the new features of HTML5 which support advanced web developments, and listed down the Uses of HTML in the Real World. 

What is HTML?
HTML, expanded as Hyper Text Markup Language is a standard markup language used in the creation of web pages. HTML combined with CSS (Cascading Style Sheet) and JavaScript takes web development to an advanced level. The formatting tags, image, video, anchor, and hyperlink tags help structure the web page in a variety of ways. HTML also allows us to include header and footer sections on our HTML page.

The introduction of HTML5 is said to have brought a lot of advancements in web development. Semantic HTML elements have brought more specific elements into the picture and made even the role of developer easy to understand and modify the code. Nav, mark, aside, section, blockquote, etc are examples of semantic HTML elements.

HTML Basic Structure
html-structure
HTML Basic Structure
Top 10 Uses of HTML in the Real World
As said by many, HTML projects boost our profile and ensure a bright career ahead. It is essential to know the various applications of HTML in this regard. We could list down a lot of uses of HTML, let us dive deeper into a few essential ones.

1. Web Pages Development
Different websites we see on the internet regularly are in some form written in HTML code. As mentioned earlier HTML is used to structure the web page in various ways. We could include different sections, insert tables, and split the web page. With the introduction of Semantic HTML elements in HTML5, HTML has made hassle free even for the developer to understand and modify his/her code better. 

Apart from the elements, we can style different types of web pages like the landing page, parallax pages, grid orientation pages, etc. Styling and manipulation of HTML elements are comparatively easier and more effective with CSS and JavaScript.

2. Navigating the Internet
HTML is an essential element in navigating between web pages. Navigation is possible using the hypertext concept. The linking is also simpler. From the internet user's point of view, they click on a text which takes them to the next page. HTML facilitates navigation by hyperlinking with the help of an anchor tag.




<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<a href="geeksforgeeks.org"> Click here to open! </a>
</body>
</html>


Navigation can increase visitors to a website. It increases user activity on the website. It also helps the web user to look at the content structure and organization.

3. Responsive Designs
what-is-Responsive-Design
Responsive Design

The integral part of a web page is for it to be interactive and responsive to the user. HTML makes it possible. Unlike static pages, responsive ones also have a better reach. Automatically resizing, hiding, shrinking, or enlarging a website to make it look good on all devices (desktops, tablets, and phones) is what a responsive web design is made of where HTML and CSS aid the purpose. 

<meta> tag is used on all pages to create a responsive website. In addition, images could be made responsive with the help of the width property in CSS. Texts can also be made responsive by setting it up with a "VW" unit, which means the "viewport width".

4. Storage Function in the Browser
Storage of data in the browser was tedious in the past. For a user to save the data of the browser that persists between two sessions, the user's cookies or infrastructure is to be built from the server end. This process has now been eased with HTML5. HTML5 has roped in new features. Such storage features are localStorage and IndexDB.  

The web storage objects window.localStorage and window.sessionStorage store data with no expiration date and storage for one session respectively. The localStorage object will have the data saved even when the browser is closed. setItem and removeItem are the functions commonly used to store and remove data from the storage. Also, the most important part is that these features are supported by all browsers.

To Store - localStorage.setItem("username", "Nisha");
To Retrieve - document.getElementById("result").innerHTML = localStorage.getItem("username");
To Remove - localStorage.removeItem("username");
5. Data Entry Support
With many other features that we have been discussing, here's another important one to be taken into account which is data entry. For so long we have stored data in dedicated files for this purpose. HTML5 paves way for data entry online, that is to obtain the data to store, from the user via forms. In this case, we have HTML tags like <form>. 

Syntax for <form> tag

<form>
      <!--form elements-->
</form>
Other elements include input which may be a drop-down box, list, text box, password box, etc. On the whole, HTML makes the process of data entry easy and effective which also includes validations with the help of Javascript.

6. Creation of Web Documents
HTML is predominantly used in creating web documents on the internet. DOM (Document Object Model) is used in the creation of web documents. In addition, HTML tags are used in formatting the document. The HTML web document begins with the declaration of <!DOCTYPE html>. Further, it proceeds with the usual HTML opening and closing tags. The HTML DOM model is constructed as a tree of objects. 

The root element is the <html> which is divided into head and body. The Head contains the title of the page or document. The body consists of the content which is built using various elements such as headings, paragraphs, line breaks, anchors, etc. Further down the tree is the attributes of the elements. For instance, anchor tag <a> has an attribute say, 'href'. 

7. Game Development
We see in recent days, from kids, and teens to adults all of them are drowned in online games. Let us get to know the role of HTML in the creation of such games. Earlier game developments were specific to platforms like Flash. However, HTML5 offers many options and features for game development. Beginners can start with HTML elements such as canvas which offers all the functionality needed for making games.


<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<canvas id="canvas" width="200" height="100"> </canvas>
</body>
</html>





<script>
var c = document.getElementById("canvas");
var ctx = c.getContext("2d");
ctx.moveTo(0, 0);
ctx.lineTo(200, 100);
ctx.stroke();
</script>


Javascript could be used to draw, insert images, write, etc into the canvas. CSS3 is an advanced version of Cascading Style Sheet used in structuring, styling, and formatting. Various components, controllers, etc are added making the game lively. Thus, it is no longer a big deal to develop games.

8. Offline Web Applications
We know, it is always necessary to have internet connectivity to view web pages. However, nowadays web applications could be accessed even when we are offline. The user will be able to access the data with the help of HTML. It uses a cache manifest file to determine which data to store while offline. 

In case you are travelling outside your Internet Service Provider's Coverage Area, your connection is likely no more available. In this case, the user provides a manifest that lists the files which are needed for a web application to work offline. This causes the user's browser to have a copy of the files for offline use.

9. Cutting Edge Feature
Cutting-edge is often used to describe disruptive technologies as well as the latest technological advancements. As we have looked so far, HTML5 has brought in many changes and advancements in web development. Cutting-edge web design trends include animated HTML headers, embeddable infographics, designing around illustrations with CSS, scroll-triggered call-to-action, user badges, etc.  

Google Chrome serves to be an excellent choice of browser for the use of HTML's recent set of standards and APIs. It lets the libraries download the required packages dynamically whenever required.

10. Enrich the Website
HTML allows the use of Native APIs to enrich the website. With the many features that HTML5 has introduced, it has also introduced many tools and capabilities that were never expected before. APIs like visibility, full screen, and media capture could be used to improve the experience of applications. 

The APIs effectively allows us to do the background work independently of other UI scripts, without affecting the performance of the page. The major role of these APIs is to create custom controls and functions.

Conclusion
In the above article, we have discussed in detail the applications of HTML apart from conventional web development. With almost everyone having access to a device connected to the internet, it is now possible to gather all of the required information. We now know that HTML lets us build games, serves as storage, allows offline web applications, enriches websites, and data entry, creation of web documents, responsive designs, navigation purposes, and so on. 

