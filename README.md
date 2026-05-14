# rails_subdirectory_app

## Tested Environment

- Ruby 3.4.9
- Rails 8.1.3


## Setup for RubyMine

This Rails application is located under the `rails_backend` directory. To make RubyMine recognize it as a Rails project, mark `rails_backend` as a Ruby Module Root.

1. Open Settings/Preferences in RubyMine and check `Languages & Frameworks`. At first, Rails is not listed.

   <img src="docs/images/language-frameworks-without-rails.png" alt="Languages & Frameworks without Rails" height="600">

　  

2. In the Project view, right-click the `rails_backend` directory, then select `Mark Directory As` > `Ruby Module Root`.

   <img src="docs/images/rubymine-ruby-module-root-setting.png" alt="Mark rails_backend as Ruby Module Root" width="800">

　  


3. Open `Languages & Frameworks` in Settings/Preferences again. Rails is now listed.

   <img src="docs/images/language-frameworks-with-rails.png" alt="Languages & Frameworks with Rails" height="600">

　  


4. Start the Rails server from Run in RubyMine. When it starts successfully, the Rails server logs appear in the Run tool window.

   <img src="docs/images/rubymine-rails-server-started.png" alt="Rails server started from RubyMine" width="800">

　  


5. Open the Rails application in a browser and confirm that the page is displayed.

   <img src="docs/images/rails-app-running-in-browser.png" alt="Rails app running in browser" width="800">
