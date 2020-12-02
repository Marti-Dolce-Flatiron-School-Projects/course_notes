# Learn-Co gem installation
Install using gem learn-co

* See Additional Commands
[https://github.com/Marti-Dolce-Flatiron-School-Projects/course_notes/blob/main/learn-co%20gem]

# Mass Delete Github Directories/Files
[Per @nadiajoyce GitHub Alumni](https://github.community/t/how-to-delete-multiples-files-in-github/702/2)
## The steps for doing this are:

- In the command-line, navigate to your local repository.
- Ensure you are in the default branch:
- git checkout master
- The rm -r command will recursively remove your folder:
- git rm -r folder-name

### Commit the change:
- git commit -m "Remove duplicated directory"
- Push the change to your remote repository:
- git push origin master

# Baseline project setup cheats

- [x] Generate spec tests + gem files. Res. bundler
```ruby
  % rspec --init: creates .rspec and spec.rb
  % bundler init: creates project gemfile
  % add requirements to gemfile/gemfile.lock
  % use bundle install to update/add gems
  % if using a rakefile, include in gemfile
```
- [x] Generate rake file (If necessary).  A rake file automates functions required to build, test, package and install programs. Res. rake
	
```ruby
#NOTE:  If using terminal example**
echo "source 'https://rubygems.org'" >> Gemfile
echo "gem 'rake'" >> Gemfile
bundle install
bundle exec rake -T
```
- [x] Generate environment.rb map paths
* Add story, author category RB's to environment
* Add environment.rb with path (require\_relative) to spec_helper
* Make sure environment.rb has links to lib files 

- [x] Code Classes & Methods, then Test
```ruby
#NOTE: Tracks contexts and describe formats
rspec --format=documentation
#=> Returns spec documentation:
Author
  has a name
  with stories
    #stories
      has an empty array of stories when initialized ...
```
- [x] Create Console to visually test
* Add rake file
* Add rakelib (if required)
* Add lib with modular tasks (if required)
* Add tasks or task files (in namespace)
* Declare all required dependencies
* Add prerequisites
