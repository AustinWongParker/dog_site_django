### FAQ
Q: Projects vs. Apps?\
A: What’s the difference between a project and an app? An app is a web application that does something – e.g., a blog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.

Q: Why does django create a new directory when I make a new app?\
A: Django does this automatically and you'll have to add . at the end of it to create it in the same directory.

Q: What do we add to our INSTALLED_APPS?\
A: We need to add the new apps we create into the settings.py INSTALLED_APPS list.

Q: Where are apps in relation to the file structure?\
A: For this specific project, we will want it on the same directory as dog_site. So, if we created a posts app, it will be in dog_site_django AND on the same layer as dog_site.

Q: Flow?\
A: Create project -> create app (like polls/blog) -> create model (models are our objects. This is where we define our 'blog' posts -- Remember, models are how we maintain the data.) -> create tables for models in your database\
    - Check how_to_run for commands on migrations

Q: How do I add, edit, and/or delete posts (or whatever app you have) that you modeled it after?\
A: You can use the Django Admin