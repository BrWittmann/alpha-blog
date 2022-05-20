#when making new ruby app in windows:
#html in emmet: *.erb:html ruby:html

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data'

#Steps: 1. Remove ", platforms: [:mingw, :mswin, :x64_mingw, :jruby]" in Gemfile for "gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]"
#2. Run gem uninstall tzinfo-data
#3. Run bundle install


gem 'net-smtp', require: false

#Install yarn using your OS package manager, or take a look at https://yarnpkg.com/en/docs/install
#Set it up rails webpacker:install
#Make sure all packages are up to date yarn install --check-files
#Start your Rails server rails s


when the ms counter is showing on rails server:
just remove the gem rack-mini-profiler in your gem file. Then run bundle install in your command prompt. If you are a beginner its not going to be useful.


git commands:
first time setup:
git config --global user.name "Your name"
git config --global user.email youremail@example.com

git config --list
to verify

in rails server

git add -A #track files

git status #shows files that are being tracked

git commit -m "" #-m is for message. give message when committing 


downloading a Ruby app to another computer to continue work:
in CMD go to folder where you want your app to be cloned to, for example cd C:/my_apps/
login to github and go to app you want to clone, press green button "Clone or Download", you will see SSH link, copy it.
in CMD run git clone git@github.com:user/my-app.git (use SSH link you copied)