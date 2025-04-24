# lab2

# Delete branches

 remove branches locally
 --> git branch -d name_branche (dev,teast)

remove branches remotely
 --> git push origin --delete name_branche (dev,teast)
 or
 --> git push origin :branch_name
 
# to checkout another branch without commit changes
 we use ---> git stash.
 If you want to revert the changes later
 --> git stash pop

 # To list all tags
  git tag

# To delete remote tag
  git push origin --delete v1.7
# To delete local tags
  git tag -d v1.7


