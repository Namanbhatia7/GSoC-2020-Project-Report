# GSoC: Improvement of Uyuni Publishing Theme

**Organization**: openSUSE  
**Mentors**: Joseph Couyette and Pau Garcia.  

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
                  Content Section is also modified and given a new look and follows the section on which User is. Also, Left-nav bar is improved and Current Module is highlighted. Few Bugs were also fixes.  
                  
#### Pull Request:  

**Link:** https://github.com/uyuni-project/uyuni-docs/pull/389    
**Status:** Merged.                    
                  

