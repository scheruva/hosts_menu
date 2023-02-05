# hosts_menu
Configurable Menu based approach to ssh logins

## ONE TIME SETUP
Add the directory containing these scripts to your path
```bash
echo >> ~/.bashrc
echo >> "PATH=${PATH}:<HOSTS_FILES_DIR>"
source ~/.bashrc
```

## USAGE
Step 1: Edit the main.hosts
Step 2: Add as many <group>.hosts file you need and fill it with the appropriate hostnames
Step 3: Do the one-time setup (see block above)
Step 4: Run
```bash
hosts
```
