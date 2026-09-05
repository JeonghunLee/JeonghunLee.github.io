# Documentation      

??? note "Quick access and Contact"   
    **Icon links** to my platforms are available at the bottom of this page.     

## Technical Blog  

- :fontawesome-brands-blogger:  [My Technical Blog](https://ahyuo79.blogspot.com?m=0)    
    **Tag-based Categories, only PC (not Mobile)**   

| Information   | Tags |  
| ------------- | -----| 
| DevOps – CI/CD / Docker | [DevOps-CI/CD](https://ahyuo79.blogspot.com/search/label/DevOps-CI%2FCD) / [DevOps-Docker](https://ahyuo79.blogspot.com/search/label/DevOps-Docker) |  
| DevOps-Docs | [DevOps-Sphinx](https://ahyuo79.blogspot.com/search/label/DevOps-Sphinx) / [DevOps-MkDocs](https://ahyuo79.blogspot.com/search/label/DevOps-Mkdocs) / [DevOps-ReadTheDocs](https://ahyuo79.blogspot.com/2021/06/readthedoc-doc-host.html)  |
    

!!! tip "How to use these links"
    Click each **Tag link** to view all related posts at once.  
    All links redirect to my technical blog (Blogger), organized using **tag-based categories**    
    The blog is primarily written in Korean, with **English support available via Google Translate**.

 Go Back **[Technical-Skills->DevOps-CI/CD/CT](project_technical_skills.md#devops-cicdct)**  

<br>

## ReadTheDocs-Projects  

<br>
<br>

ReadTheDocs is retained for documentation hosting experiments and legacy project documentation.

* **WIFI Sniffer**    
    * :material-arrow-left: Project [ESP-Series → WIFI Sniffer](project_esp_series.md#wifi-sniffer-esp32-s3)   
    * :fontawesome-solid-book: DOC: https://wifisniffer.readthedocs.io/ko/latest/   
    * :fontawesome-solid-screwdriver-wrench: CFG: https://app.readthedocs.org/projects/wifisniffer/    


**API Documentation Integration**

The WIFI Sniffer project also compares several approaches for integrating **C/C++ API documentation** into Sphinx and ReadTheDocs.


| Configuration | Purpose | API Document |
|---|---|---|
| **Sphinx + Doxygen** | Generate API documentation directly from C/C++ source comments using Doxygen. | [API Reference-1](https://wifisniffer.readthedocs.io/ko/latest/api_sphinx_doxygen.html) |
| **Sphinx + Doxygen + Breathe** | Import Doxygen XML into Sphinx so API content uses the Sphinx document structure, theme, and navigation. | [API Reference-2](https://wifisniffer.readthedocs.io/ko/latest/api_sphinx_doxygen_breathe.html) |
| **Sphinx + Doxygen + Breathe + Exhale** | Automatically generate a structured API hierarchy on top of Breathe, including files, functions, types, and related API pages. | [API Reference-3](https://wifisniffer.readthedocs.io/ko/latest/api/api_root.html) |


!!! note "ReadTheDocs Hosting and Sphinx API Documentation Flow" 
    ReadTheDocs is used to host the generated technical documentation.  
    **Doxygen** extracts API information from C/C++ source code.   
    **Breathe** connects the generated Doxygen XML to Sphinx.  
    **Exhale** automatically builds a navigable API hierarchy from the Breathe/Doxygen data

!!! Warning "ReadTheDocs sometimes not working properly (Server Problem)" 


<br>

[:fontawesome-solid-screwdriver-wrench: View ReadTheDocs Dashboard](https://app.readthedocs.org/dashboard/)    


<br>

---

### ReadTheDocs TEST  

<br>



!!! note "ReadTheDocs TEST Hosting Site and Repository"


<br>

* ReadTheDoc test00
    * :fontawesome-solid-globe: WEB: https://readthedoc-test00.readthedocs.io/en/latest/  
    * :fontawesome-brands-git-alt: GIT: https://github.com/JeonghunLee/readthedocs.org   

<br>

* ReadTheDoc Template TEST       
    * :fontawesome-solid-globe: WEB: https://jeonghunlee-demo.readthedocs.io/en/latest/


<br>

## Github Pages-Projects    

<br>
<br>

* Go Back [ESP-Series->WIFI Sniffer Project](project_esp_series.md#wifi-sniffer-esp32-s3)       
    - :fontawesome-solid-book: DOC: https://jeonghunlee.github.io/wifisniffer/  

<br>

* Go Back [AI->AI-Agent with MCP Project](project_ai.md#ai-agent-with-mcp)       
    - :fontawesome-solid-book: DOC: https://jeonghunlee.github.io/local-ai-agent-mcp/   

<br>

* Go Back [AI->AI-driven Embedded Continuous Testing](project_ai.md#ai-driven-embedded-continuous-testing)       
    - :fontawesome-solid-book: DOC: https://jeonghunlee.github.io/AI-driven-CI-CT/
    - :material-test-tube: Pytest Results: https://jeonghunlee.github.io/AI-driven-CI-CT/tests/pytest/index.html
    - :material-test-tube: Unittest Results: https://jeonghunlee.github.io/AI-driven-CI-CT/tests/unittest/index.html


??? note "Technical Writing and Documentation Automation"
    Technical documents are maintained using **MkDocs** and **Git-based version control**.     
    Documentation and TEST reports are published through **GitHub Pages** as part of the project workflow.     


<br>

---

### GitHub Pages-MyProfile    


<br>


* Github Hosting Site Main and Repository (Current Git)
    * :fontawesome-brands-git-alt: GIT: https://github.com/JeonghunLee/JeonghunLee.github.io
    * :fontawesome-solid-globe: WEB: https://jeonghunlee.github.io/    

!!! note "Github Main Hosting Site and Repository"


<br>

---


### GitHub Pages TEST 

<br>

various tests based on Github Pages (only for Test)    

!!! note "Github TEST Hosting Site and Repository"

<br>

* Github Pages based on Jeklly   
    * :fontawesome-solid-globe: WEB: https://jeonghunlee.github.io/blog/
    * :fontawesome-brands-git-alt: GIT: https://github.com/JeonghunLee/blog

<br>

* Github Pages based on Jeklly 
    * :fontawesome-solid-globe: WEB: https://jeonghunlee.github.io/minima/
    * :fontawesome-brands-git-alt: GIT: https://github.com/JeonghunLee/minima/settings/pages

<br>

* Github Pages based on Jeklly 
    * :fontawesome-solid-globe: WEB: https://jeonghunlee.github.io/github-pages-with-jekyll/
    * :fontawesome-brands-git-alt: GIT: https://github.com/JeonghunLee/github-pages-with-jekyll

<br>

---






