### FAQ
Q: Projects vs. Apps?\
A: What’s the difference between a project and an app? An app is a web application that does something – e.g., a blog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.

Q: Why does django create a new directory when I make a new app?\
A: Django does this automatically and you'll have to add . at the end of it to create it in the same directory.

Q: What do we add to our INSTALLED_APPS?\
A: We need to add the new apps we create into the settings.py INSTALLED_APPS list.