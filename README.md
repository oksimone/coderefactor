To the viewer:

This is my first homework assignment in my fullstack bootcamp. Going into this assignment, I thought it'd be as simple as changing a couple of tags and classes. But it was much more than I had anticipated... I struggled a lot with trying to clean up the stylesheet. Everytime I tried to alter the CSS code, the webpage would make a massive change. With trial and error and  "Google FU'ing" I resolved a good bit of my CSS question. I'm sure there are still some mistakes in my code, but I worked on this to the best of my ability, and I can't wait to see what my work will look like 10 weeks from now. Below is a description of how I went about cleaning up the code. 

Before I started "cleaning" up the code, I analyzed the entire HTML code as well as the stylesheet and noted a couple of things. 

1. There is no header section or navbar
2. There are multiple div's throughout the entire code. 
3. There is an aside and footer tag, but they're both wrapped in a div tag
4. I noticed that none of the images have alt tags
5. I also noticed that "Search Engine Optimization" doesn't have an id, like "Online Reputation Management" and "Social Media Marketing". 
6. On the CSS code, there were a multiple classes that had the same property. which made the code seem much longer than it was
7. And, the CSS code wasn't in the same order as the HTML code. 

From my code, I know that I needed to add/change the following:
1. a header section
2. a navbar inside the header section
3. a main element for the 3 different sections
4. an aside element
5. a footer section
6. change the title 
7. fix the order of the css code and condense the code

- The first thing I did was change the header "div class" to "nav class." Then, I deleted the div tags that wrapped the &lt;ul&gt; and replaced them with &lt;nav&gt; tags. After that, I wrapped the nav tags with header tags.

- I only left one div tag in the code, which was the hero. I didn't think it was necessary to change the tag. 

- Then, I wrapped the three different sections and the aside in a main tag. 
- added section tags to the three different section 
- added an id to "search engine optimization" because it was missing in the original code. 
- added alt tags to the three photos on the page
 added aside tags
- Then I wrapped the footer content in a footer tag, 
    - The foooter also had an h2 tag, so I changed it to an h4 tag in the HTML & CSS code
- I changed the title of the page and a small description.
- I then condensed the benefits class so that they're in one class, as  opposed to three. I did the same with the content classes as well.


