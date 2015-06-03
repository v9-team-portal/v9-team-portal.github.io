#The v9 Team Portal
###[v9-team-portal.github.io](http://v9-team-portal.github.io/)

*All changes can be made committed on github*

### To edit an existing card
1. Navigate to the _posts file
2. Choose the file corresponding to the card you wish to edit
3. Make changes and commit to master branch

### To create a new card
1. Navigate to the _posts file
2. Create a new .md file which need to be named in the following format:
        2015-01-01-card-1-[name].md
3. Cards need to have the following layout 
      ```html
      ---
      group: "[card title]"
      color: "[accent color]"
      icon: "[font-awesome icon]"
      ---

      <h5><a href="[link]">[link description]</a></h5>
      ```
4. Commit changes to master branch
