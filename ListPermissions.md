# Change to the 'projects' directory
     cd projects

# List the contents of the 'projects' directory with detailed permissions
       ls -l

# List all contents, including hidden files, with detailed permissions
       ls -la

# Remove write permission for others (o-w) on 'project_k.txt'
       chmod o-w project_k.txt

# Remove read permission for the group (g-r) on 'project_m.txt'
       chmod g-r project_m.txt

# Remove write permission for the user and the group, and add read permission for the group on '.project_x.txt'
       chmod u-w,g-w,g+r .project_x.txt

# Remove execute permission for the group on 'drafts' directory
       chmod g-x drafts
