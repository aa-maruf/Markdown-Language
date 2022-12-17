# 👋Welcome to markdown language tutorial

#### Note: `.md` means markdown documents.


---
## Table of Contents:
- [Quote](#quote)
- [Image](#image-link)
- [Adding link](#adding-link)
- [Italic/bold alphabet](#italicbold-both-)
- [List](#list-)
- [Table](#table)
- [Code block](#code-block)
- [Header link](#header-link)
- [ Horizontal rule](#horizontal-rule)
---

  
 - ### Quote
   
   > `>` sign is used for quote.
  >> `>>` is used for  nested quote.

     

 <!--    "  > " is used for quotes     -->

---


- ### Image Link:
```markdown
  <!--   Markdown syntax    -->
  ![Alt text](.Images/Git-and-Github-bangla-tutorial- 
 13-Markdown-crash-course-YouTube.png)
```
```html
 <!--   HTML syntax    -->
 <img src =".Images/Git-and-Github-bangla-tutorial-13- Markdown-crash-course-YouTube.png" width="400" title="Alt text" /> 
```
```c
Demo (Markdown):
```
![Markdown Demo](./Images/Git-and-Github-bangla-YouTube.png)
```c
Demo (HTML):
```
<img src ="./Images/Git-and-Github-bangla-YouTube.png" width="400" title="HTML Demo" />

---


- ### Adding link:
  - Automatic Link :
         `Demo:`www.facebook.com
    
    ```c
    /// Directly add Link. It will be auto genarated. 
    
     ```
    
  - Disable Link :
          `Demo:` `www.facebook.com`
  ```markdown
   <!--   Markdown syntax    -->
  /// To disable a link,write the link inside 2 backtic symbol (`)
    `www.facebook.com`
  
  ```
  -  Markdown Link :
     `Demo:` [Facebook!](www.facebook.com "Tooltip")
    
  ```markdown
  <!--   Markdown syntax    -->
     [text](www.Link.com) 
      
  ```
  
  
---
- ### Italic/bold /both :
    `Demo:`
   _Italic_
    **Bold**
    __Bold__
    ***Both***
   ```markdown
      <!--   Markdown syntax    -->
  
    _Italic_
  
    **Bold**
  
    __Bold__
  
    ***Both***
   ```
 


---


- ### List :
   - Ordered List
     
        ```markdown
         <!--   Markdown syntax    -->
          1. one
          1. two
          1. three
        ```
     `Demo:`
        1. one       
        1. two
        1. three
         
  ---
  
  - Unordered List :
    
      ```markdown
     <!--   Markdown syntax    -->
       - Part1
       - part2
       - part3
      ```
      `Demo:`
       - Part 1
       - part 2
       - part 3
         
  ---

  - Task list :
    ```markdown
      <!--   Markdown syntax    -->
     - [x] Topic 1
     - [x] Topic 2
     - [ ] Topic 3
    ```
    `Demo:`
    - [x] Topic 1
    - [x] Topic 2
    - [ ] Topic 3

---


- ### Table: 
 ```markdown
    <!--   Markdown syntax    -->
    
   | Name | Email | Comments |
   | --- | --- | --- |
   | Put your Name Here | Put email here |
   
 ```
 `Demo:`
   | Name | Email | Comments |
   | --- | --- | --- |
   | Abdullah Al Maruf | aamaruf2000@gmail.com |
   | Mahdi Hasan | the.madhi.hasan@gmail.com |
   | Put your Name Here | Put email here |
   
---


- ### Code block:
  
  
   - Inline code block: Demo -> `Syntax`
     ```markdown
       <!--   Markdown syntax    -->
     
       `Syntax`  ///write code inside 2 backtick symbol
     ```


  - Multiple Line code block:</p>
    `Demo:`
      ```c
          ///Demo:
          #include<stdio.h>
            void main(){
            printf("Hello world\n");
            }
      ```
    
    ```markdown
     <!--   Markdown syntax    -->
    ```c
       ///starting with 3 backtick+             programming language name (optional)
  
         code
  
    ```  ///ending with 3  backtick

    ```
---


- ### Header Link:


    `Demo :` Clicking on [Table of Contents](#table-of-contents) will take you to the "Table of contents" header of this page.
  ```Markdown
  <!--   Markdown syntax    -->
     [Text](#Header-file-name)
  ///For space inside header file name,use hyphen.
  Example:
    [Table of contents](#table-of-contents)
    
  ```
---


- ### Horizontal rule:


  ```markdown
  <!--   Markdown syntax    -->
  ---
          Hello
  ---
  ```

---




  
