# **Object Relationship**
An object relationship is a connection between two objects.
Think of it as a link between two objects.
Suppose we have two departments, one for sales and one for marketing.
And the person who is in common or both departments is called a common person.
Now there will be a relationship between the sales department and the marketing department.

In salesforce we have different types of object relationships.
We can create relationships between standard objects, custom objects, or both.

1. **Lookup relationship** :
A lookup relationship is a one-to-one relationship.
It is used to link records from one object to another.
we can say that a lookup relationship creates a relatively loose connection between two objects.
Suppose a company is selling course to student and they have two object, Course and Student.
a student X is enrolled in course Y.
Now there will be a lookup relationship between student X and course Y.
The course field can be a lookup field pointing to course Y.


2. **Master Detail relationship** : 
A master detail relationship is a one-to-many relationship.
It is used to link records from one object to another.
we can say that a master detail relationship creates a relatively tight connection between two objects.
Suppose a company is selling course to student and they have two object, Course and Student.
a student X is enrolled in course Y.
Now there will be a master detail relationship between student X and course Y.
The student field can be a master detail field pointing to student X.

While lookup relationships are fairly casual, master-detail relationships are a bit tighter. In this type of relationship, one object is the master and another is the detail. The master object controls certain behaviors of the detail object, like who can view the detail’s data.


---------------------------------------- 

## **Create custom object**
1. Click the Object Manager tab.
2. Click Create | Custom Object in the top-right corner.
3. For Label, enter FavoriteCopy.
4. For Plural Label, enter FavoritesCopy.
5. Check the box for Launch New Custom Tab Wizard after saving this custom object.
6. Leave the rest of the values as default and click Save.
7. On the New Custom Object Tab page, click the Tab Style field and select a style you like.
8. Click Next, Next, and Save.


-----------------------------------------


## **Create lookup relationship**
1. From Setup, go to Object Manager | Favorite.
2. On the sidebar, click Fields & Relationships.
3. Click New.  
4. Choose Lookup Relationship and click Next.
5. For Related To, choose Contact. For the purposes of DreamHouse, contacts represent potential home buyers.
6. Click Next.
7. For Field Name, enter ContactCopy, then click Next.
8. Click Next, Next, and Save.


---------------------------------------

## **Create master detail relationship**
1. On the Object Manager page for the custom object, click Fields & Relationships.
2. Click New.
3. Select Master-Detail Relationship and click Next.
4. For Related To, choose Property.
5. Click Next.
6. For Field Name, enter PropertyCopy and click Next.
7. Click Next, Next, and Save.
