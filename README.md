At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation? Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out? If your project has a lot of features, consider adding a heading called "Features" and listing them here.

README.md

For this assignment, we were tasked at not only cleaning up the code for screen readers, but to make it more accessible for those who may have difficulty navigating the maze of code. I wanted to not only make the code itself look good, but to make sure all elements made sense and that all the semantics were properly placed. 

For example, at the top of the Horiseon webpage you will find 3 links you can click on to take you to a lower spot on the webpage. These 3 titles (search-enging-optimization, online-management-reputation, and social-media-marketing) when clicked will take you to their respective spots. In coding it is common to use a <div> tag for such a purpose. But since I wanted to make it more accessible, I named this container as <nav>, which is short for navigation. 

So prior to this the code featured many different <div> tags that were able to be replaced by numerous different semantic elements that functioned the same was as <div>, but were easier to understand in the context of the webpage. 

Here are examples of the semantics I used to replace some <div> tags:

<main>
<section>
<aside>
<footer>
<nav>

This should make it easier for people to understand the thought process behind the coding.

In doing this however, the CSS file was in need of altering in order to make the HTML file be displayed properly. 

If you had a <div Class="title"> section in your HTML for example that was to be the main portion of the webpage, you would first change that to <main>, and then in CSS you would change it from

.title {}

into

<main>

Notice that I took out the period. This is essential in making the code work properly when using semantic elements besides the <div> tag.

Apart from that, I made sure to have the sections in CSS reflect the order that the HTML document was in. I wouldn't start my CSS with FOOTER for example, and I would make sure that the order was where it needs to be to make sense for anyone looking at the code.

Overall this was a deceptive little assignment as you think you have it figured it out and that it was simple, but there was actually more work to be done!

                    