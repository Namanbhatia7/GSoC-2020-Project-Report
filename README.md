# GSoC: Improvement of Uyuni Publishing Theme

**Organization**: openSUSE **(Uyuni)**   
**Mentors**: Joseph Cayouette and Pau Garcia.  

# Description  
Uyuni documentation is based on Antora which generates Site with a default UI features. The Project aimed at **Improving** the Current UI of Uyuni documentation Site and improve **existing features like Admonition blocks, Tables, Adding whitespaces and other UI macros**. It also involved improving **User Experience** by making a **modern** and **classy** UI but at the same time **simple** so that Users Eye easily catch information they are looking for. **It is to ne noted that a Simple layout is the key to keep readers interested.**  

# Code
Below is the list of Add-ons and modification of UI Features:

- ###  Admonition Blocks:
THe first feature I worked on was Adminition Blocks. Admonition blocks holds a lot of importance as they draw attention of reader to content with special label and Icon. Uyuni documentation contains mainly three kind of admonition blocks ie. **IMPORTANT, NOTE and WARNING**. I designed them to keep their identity separate from each other by giving each admonition block it's own Color and Icon.

#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/311  
**Status:** Merged.  

- ### Tables and Pre Blocks:  
When designing Tables, Readability must hold the utmost importance. I used Zebra Stripes for designing Tables ie Using alternating different colors for each row with a header contrast so as to differentiate Header text from Column text. Pre Blockquote design was also modified to make it look clean and neat.

#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/323  
**Status:** Merged.  

- ### Search Results and drop-down:
Uyuni integrates lunrjs Search. Previously, Uyuni search bar display Module name and text in search drop-down. Searched Text is improved by increasing length of string returned and giving more relevant results. Another column is added in search results, ie Guide Name, that displays the Parent Guide of the Module displayed in drop-down. Also, Column name is added so that It become readable and user friendly    

#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/364   
**Status:** Merged.  

- ### White-Spacing and Other Features:  
White-Spacing is space between Screen elements. White-space is very important feature to get viewer attention. It ensure design is readable, easy to understand and easy to like.
Margin and padding is added between different UI components like, Paragraphs, Admonition Blocks, Tables, Images etc. Current Site content is made more breathable. Each Section is given sufficient space between them with HR rules to separate them.  

Content Section is also modified and given a new look and follows the section on which User is. Also, Left-nav bar is improved and Current Module is highlighted. Few Bugs were also fixed.  
                  
#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/389 and https://github.com/uyuni-project/uyuni-docs/pull/369     
**Status:** Merged.  

- ### Error Page:  
It is realy important to design a good Error page to retain visitor. If Visitor reached the page in error, it should reflect the personality of site. Error page is designed by keeping Uyuni theme in Mind and kept as simple as possible. Also, an error page should load as quickly as possible. To ensure that I used Svg instead of Jpg or Png.  


#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/404 (**Fun Fact**: *error-404-page landed on PR #404* :joy:)      
**Status:** Merged.  

- ### UI macros:  
Inline buttons and icons were updated.  

#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/443     
**Status:** Merged  

- ### Language Selection:  
A feature to select and translate Site in particular language is proposed. A drop-down menu is added in navbar so that visitor can select language from provided options and site get load up in that language. 

#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/418    
**Status:** Open  

- ### Image blocks and other fixes:  
Image blocks are designed , margin added when two blocks are encountered simultaneously.

#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/456    
**Status:** Open  

# Conclusion 
Working with Uyuni was a great experience. To implement the knowledge and when the code written by you goes live gives immense pleasure. My summer was fun-filled with lots of learning experiences. It was a great experience to work along with community developers as I got to learn so much from them.  

I would like to thank my mentors for their help in solving my doubts and providing valuable suggestions. A special thanks to Lana Brindley for reviewing my code and designs and helping me.  

I plan to keep contributing to Uyuni even after GSoC ends with whatever knowledge I have, be active on channel and help others. 

                  

