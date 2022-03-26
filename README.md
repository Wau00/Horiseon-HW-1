# Horiseon-HW-1
# UCB-BOOTCAMP-HW-01 HTML, CSS, and Git: Code Refactor 

* Objective: Refactor an existing code that meets the accesibility standards, becoming optimized for search engines.

# Acceptance Criteria

* The webpage meets accessibility standards
* Addresses semantic HTML elements
* The elements follow a logical structure independent of styling and positioning
-Includes accesible alt attributes in images
-Heading attributes fall in sequential order
-Incorporate a concise, descriptive tittle

# Modifications on the HTML 

- Added a reset.css stylesheet
- Changed tittle to "Horiseon" 
- Replace <div> for <header> tag
- Replace <div> for <nav> tag
    #Changed to .header nav on CSS
- Changed class name from hero to bannerAD
- Replaced <div> to <main>
- Changed class name from content to body-content
- Changed class ="search-engine-optimization" to id=                       "search-engine-optimization"
- Eliminate class = "online-reputation-management"
- Eliminate class = "social-media-marketing"
- Replaced <div> to <aside>
- Changed class= "benefit-lead", "benefit-brand", "benefit-cost" to id=     "benefit-lead", "benefit-brand", "benefit-cost"
- Replace <div> to <footer>
- Added alt properties with description to each image

# Modifications on CSS
- Restructure and organize header, body, aside, and footer elements.
- Update class/id on CSS
- Reorganized the rules to provide a cascading rule application 

     # Rules that were reorganized into one group 
    
   ```
    #search-engine-optimization, #online-reputation-management, #social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px; 
   ```
    
    ```
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
    }
    ```
    
  ```
    #search-engine-optimization img, #online-reputation-management img, #social-media-marketing img {
    max-height: 200px;
    }
    ```
   
  ```
    #search-engine-optimization h2, 
    #online-reputation-management h2, 
    #social-media-marketing h2 {
         margin-bottom: 20px;
         font-size: 30px;
         font-weight: bold ;
    }
    ```
    
  ```
    #search-engine-optimization h2, #online-reputation-management h2, #social-media-marketing h2 {
      margin-bottom: 20px;
      font-size: 30px;
      font-weight: bold ;
    }
    ```

     ```
    #benefit-lead, #benefit-brand, #benefit-cost {
        margin-bottom: 32px;
        color: #ffffff;
    }
     ```
  
  ```
     #benefit-lead h3, #benefit-brand h3, #benefit-cost h3 {
        margin-bottom: 10px;
        text-align: center;
        font-weight: bold;
    }
    ```
    ```
    #benefit-lead img, #benefit-brand img, #benefit-cost img {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }
    ```
   

# Result 
With the application of concepts and the deep research on accessibility standards, we were able to produce an optimized, easy to read and effective website.


# References 
* [Web accessibility standards](https://www.w3.org/standards/webdesign/accessibility)
* [Code Refactoring](https://www.altexsoft.com/blog/engineering/code-refactoring-best-practices-when-and-when-not-to-do-it/)
* [Make a README](https://www.makeareadme.com/#template)