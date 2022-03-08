# notes taking app 
notes taking app which takes command from the terminal and performs the following functions:

Add note : Requires user to enter Title and Body of the note and adds the note to our databse (json file)

Remove note :  Requires user to enter the Title of the note they want to remove and removes that note

List notes  : Lists the title of all the notes present

Read note : Requires user to enter the title of the note they want to read and displays the body of that note on the terminal

# Adding Note
node app.js add --title="Ayush" --body="Ayush Malaye"

# Removing Note
node app.js remove --title="Ayush"

# Listing All Notes
node app.js list

# Read a Note
node app.js read --title="Ayush"

