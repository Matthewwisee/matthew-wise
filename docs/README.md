Hi 👋 My name is Matthew Wise 🦭
=============================

I am an Information Technology student with a focus in Cybersecurity.

<img src="https://github.com/Matthewwisee/matthew-wise/blob/main/images/dog.jpeg" alt="Dog" width="300"/>

### Skills 

<p align="left">
<a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" width="36" height="36" alt="Java" /></a><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a><a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a><a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a><a href="https://jquery.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/jquery-colored.svg" width="36" height="36" alt="JQuery" /></a><a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" /></a><a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/googlecloud-colored.svg" width="36" height="36" alt="Google Cloud" /></a>
                    </p>

[Link to project](https://github.com/Matthewwisee/dev-easy-project)
                    
### Socials             
                  
<p align="left">
<a href="https://www.github.com/matthewwisee" target="_blank" rel="noreferrer">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" />
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" />
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" />
</picture>
</a>
<a href="https://www.linkedin.com/in/matthew-wise-658811285" target="_blank" rel="noreferrer">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" />
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" />
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" />
</picture>
</a></p>

### Certifications

[![CompTIA Security+ ce Certification](https://images.credly.com/size/110x110/images/80d8a06a-c384-42bf-ad36-db81bce5adce/blob)](https://www.credly.com/badges/386f695c-3e08-4d99-a4c6-aba26a028edf/public_url)


### Dev Easy Search Bar Code

#### Contributors: Carly Copley, Dylan Goodwin, Laura Lemoine, Matthew Wise
[Full Code](https://github.com/Matthewwisee/dev-easy-project)
```JavaScript
JavaScript:
function search_fact() {
  let input = document.getElementById("searchbar").value.toLowerCase();
  let x = document.getElementsByClassName("card");

  for (let i = 0; i < x.length; i++) {
    if (!x[i].innerHTML.toLowerCase().includes(input)) {
      x[i].style.display = "none";
    } else {
      x[i].style.display = "list-item";
    }
  }
}
```

<details>
  <summary>JS Explanation</summary>
  <p>The JavaScript handles the "search" functionality.</p>
</details>

```diff
HTML:
<div class="search">
   <input id="searchbar" type="text" name="search" placeholder="Search facts..">
 + <button onclick="search_fact()" type="submit">
      <img
        src="https://github.com/dgoodwin-maker/dev-easy-project/blob/main/images/icons8-search-50.png?raw=true"
        alt="Search Icon">
     </button>
 </div>
```

<details>
  <summary>HTML Explanation</summary>
  <p>The HTML connects the search button to the JavaScript function.</p>
</details>

#### Attribution: https://www.w3schools.com/howto/howto_css_searchbar.asp
#### Quote: "A quote" - Barry Cumbie

