# iTop-Contact-2-CI-Tags
Adds a relationship Tag to the link table between Contacts and CI, to categorize the type of relationship

# Object 
iTop has an embedded relation available between Contacts and Functional CIs. But, in our opinion, this link miss a 'relationship' category.

For example, says that Jon and Jack are in relation with the Database 'Accountings' 

  * Jon is the Account Supervisor (He is a User of the Database)
  * Jack is the Database administrator (He is in charge of the health of the Database)

While the two users are in fact related to the database, their relationship are quite different !

So we choose to add a 'relationship' tag in this relation.

In a complete use of the 'Depends on / Impact' system, it could be a plus that, depending on the tag, some users would be seen as 'impacts' (in our case the DB administrator) and some others would be seen as 'depends on' in our case the Account Supervisor).

# Caveats

At least up to iTop 2.7 (unclear for me in iTop 3.0) , the admin GUI doesn't allow the update of tags for links classes. That is, you can see the tags in the GUI, but not update it. This is a known bug, but there's no resolution date or version as far as I know.

This is not a problem in our usage (the 'relationship' tag will most probably be updated by an iTop synchro), but this can be a problem for you 😊

## Download

As for all my extensions, just download the zip file, and copy the 'schirrms-...' directory in your extensions directory, then rerun the setup as usual.