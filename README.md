# Song Cataloegue Backend Development

This project is run on PHP and SQL, use Start Debugging to run website then follow instructions below.

Consumer view all entries:

When you open this website, entries are listed, you don't need to do anything to view all entries
When you filtered entries by any tag, click the Home in the navigation on the upper right corner then you can view all entries
Consumer view all entries for a tag:

All tags are arranged in alphabetical order in the sidebar on the right.
To view all entries for a tag, you need to click on the tag you want to query. When your mouse moves over the tag, the discolored tag text indicates that it can be clicked.
Consumer view an entry's details:

The entire card for each entries is clickable and brings you to its detail page. When your mouse move above a card or a View All button, color changing indicates a link of more information.
You can click the Home button in navigation or Back on the upper left corner to view all entries.
(Admin and/or Consumer) Insert an entry, including the file upload:

Consumer are not able to insert any entry. You can only insert entry as an admin:
To login as an admin, you need to manually visit /login the login page.
As the only permited admin you should login the system by: Username: Troy, Password: monkey, and then click Sign in or press enter to login the account.
Click Insert Entry in the navigation bar.
To insert an entry, you must type in a Song Name, select an Artist and upload an Image File, all the other are optional.
You can add up to 3 tags to a song, and each tag cannot be the same. If there are duplicate tags, you will receive a prompt.
The image design-plan/consumer/21.jpeg can be downloaded as a test case.
After editing, you can click Add song to finish your insert.
When the new song inserted, you can see it from the buttom of the Admin View All or Consumer View all page.


To see Admin side
In Admin view all entries:

in url do /adminview
login using Troy, and monkey
Admin view all entries for a tag:

In url do /adminview
login using Troy, and monkey
click any tag listed in the /adminview page at the top of the page
Edit an entry, including the updating the file upload:

In url do /adminview
login using Troy, and monkey
click the edit button on the view all page displayed in the tables
within upload reference file like 23.jpeg provided for image upload
alter form data and click update song
