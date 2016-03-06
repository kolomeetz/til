
The best thing to start your morning with in updating your dependencies.

In general run this:

`bundle update`

Then check differences in Gemfile.lock, read changelogs of corresponding gems, run tests or check things manually (though better run tests), commit and deploy. Every morning. It will keep your dependencies updated and your upgrades smooth.

If you want to update specific library, run

`bundle update rails`

If you want to update specific library to specific version, bind the version in Gemfile,

gem 'rails', '4.2.5.2'

and then run `bundle update rails`