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

- `feat: rails generate scaffold friends...`: <i>rails generate scaffold your_resource</i> automatically generates all the necessary files to create a CRUD for the specified resource. At this commit I used <i>rails generate scaffold friends first_name:string last_name:string email:string phone:string</i>

- `feat: rails db:migrate`: apply pending migrations to the databas with <i>rails db:migrate</i> 

- `feat: include friends and new friends route at navbar`

- `chore: installs devise lib`: devise is an authentication solution for rails with warden. Following [Getting Started Devise Documentation](https://github.com/heartcombo/devise?tab=readme-ov-file#getting-started)

- `feat: creates copy Devise views`: used <i>rails g devise:views</i> to created Devise views to customize later (sign up, sgn in...)

- `feat: creates 'user' model`: used <i>rails generate devise user</i>. It creates a 'model' user and configure it with the default Devise modules. The generator also configures your config/routes.rb file to point to the Devise controller.

- `feat: rails db:migrate`: After the creation of 'user' model, you need to run  <i>rails db:migrate</i> to push the new migrations to the database.

- `feat: adds auth routes to navbar`

- `fix: sign out route error`