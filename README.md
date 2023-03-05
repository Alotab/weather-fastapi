# weather-fastapi
This repo focuses on using FastAPI to build a weather-api that tracks current weather situations in every Country/State/City. 



## Templates

jinja2 template engine was used to serve the templates in `templates/index.html`
`pip install jinja2` and import `Jinja2Templates`

Created a template object
` templates = Jinja2Templates("templates")`

Declared a `Request` in the ~path ~operation of function (index function) since it will return a template

The `templates` object will render and return a `TemplateResponse`. 

A Qick look at how this was done

![<img width="813" alt="Screenshot 2023-03-04 at 11 54 05 PM" src="https://user-images.githubusercontent.com/60059672/222934301-dbb308d6-8f6d-417f-997d-328a8f6c7750.png">)

