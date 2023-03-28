In this project, you need to onboard 20 new Linux users onto a server. Create a shell script that reads a csv file that contains the first name of the users to be onboarded.

1. Create the project folder called Shell

```
mkdir Shell
```
2. Create a csv file name names.csv

```
touch names.csv
```

Open the names.csv file

```
vim names.csv
```

Insert some random names into it. (One name per line)



3. The script you created should read the CSV file, create each user on the server, and add to an existing group called developers
 (You will need to manually create this group ahead).

4. Ensure that your script will first check for the existence of the user on the system, before it will attempt to create that it.

5. Ensure that the user that is being created also has a default home folder

6. Ensure that each user has a .ssh folder within its HOME folder. If it does not exist, then create it.

7. For each user’s SSH configuration, create an authorized_keys file and add ensxure it has the public key of your current user.

