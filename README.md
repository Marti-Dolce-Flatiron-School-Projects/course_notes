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
