# What I did in every commit
To study ruby I'm following this tutorial, setp by step:
https://www.youtube.com/watch?v=fmyvWz5TUWg&ab_channel=freeCodeCamp.org


## Commits
- `feat: creates project`: 
creates a new rails project using script <i>rails new friends</i>

- `feat: generate controller home index`: creates a controller named <b>home</b> with an action <b>index</b> and its corresponding views using script <i>rails generate controller home index</i>

- `feat: make home as home page`: now we can't access <i>/home/index</i> anymore, it throws an error, but our home shows now at home page

- `feat: generate about page`: creates this new route manually 

- `feat:implements bootstrap at 'application.html.erb'`

- `feat: creates a header with bootstrap`: creates a file names <i>_header.html.erb</i>, that will be a partial showed in all the pages. Copied template from [bootstrap navbar](https://getbootstrap.com/docs/4.5/components/navbar/)

- `feat: creates about and home links at header`: to show all available routes you can use <i>rails routes</i> in terminal