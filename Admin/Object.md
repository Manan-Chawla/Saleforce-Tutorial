# **Object**
In Salesforce CRM, we think about database tables as objects, we think about **columns as fields**, and **rows as records**. So instead of an account spreadsheet or table, we have an Account object with fields and a bunch of identically structured records.

Salesforce supports several different types of objects. There are standard objects, custom objects, external objects, platform events, and BigObjects. In this module, we focus on the two most common types of objects: standard and custom.

**Standard Objects** are objects that are included with Salesforce. Common business objects like Account, Contact, Lead, and Opportunity are all standard objects.

**Custom objects** are objects that you create to store information that’s specific to your company or industry. For DreamHouse, D’Angelo wants to build a custom Property object that stores information about the homes his company is selling

Objects are containers for your information, but they also give you special functionality. For example, when you create a custom object, the platform automatically builds things like the page layout for the user interface.

--------------------------------------------------


## **Creating custom object**
1. Scroll to the bottom of this page and create a trailhead playground. Don’t skip this step! You need to use a fresh and clean Trailhead Playground for this module.
Note: Even if you're completing this module as part of the Admin Beginner trail, be sure and create a new Trailhead Playground to complete these steps. You don't need to reinstall the Dreamhouse app in the new playground org.

2. Once your playground is created (it takes a minute!), press Launch.

3. Click the gear icon The setup gear. at the top of the page and launch setup.

4. Click the Object Manager tab.

5. Click Create | Custom Object in the top-right corner.

6. For Label, enter PropertyCopy. Notice that the Object Name and Record Name fields auto-fill.

7. For Plural Label, enter PropertiesCopy.

8. Prior to saving the custom object, scroll to the bottom of the page and select the checkbox Launch New Custom Tab Wizard after saving this custom object.

9. Leave the rest of the values as default and click Save.

10. On the New Custom Object Tab page, click the Tab Style field and select a style you like. The style sets the icon to display in the UI for the object.
Click Next, Next, and Save.


------------------------


## **Fields and what are there for**
* **Identity** : 
It is an 18 character, case-insensitive identifier that uniquely identifies a record.
We can generate or use to find a records ID

* **System** :
It is a read only field that provide information about a recod from system, like when record was created or when it was last changed.

* **Name** :
All records need a names so you can distinguish between them. We can use text names or auto number name that automatically increment every time we create a record.

* **Custom** :
Field you can create on standard or custom object are called custom fields.


--------------------------


## **Creating custom fields**
1. From Setup, go to Object Manager | Property.
2. In the sidebar, click Fields & Relationships. Notice that there are already some fields there. There’s a name field and some of the system fields you learned about earlier.
3. Click New in the top right.
4. For data type, select Currency.
5. Click Next.
6. Fill out the following:
* **Field Label**: PriceCopy
* **Description**: The listed sale price of the home.Copy
7. Check the Required box.
8. Click Next, Next again, and then Save.


--------------------------


## **Creating a record**
1. From app launcher, find and select sales
2. click properties tab in nav bar.
3. click new button.
4. Enter a name and price for property and click save


---------------------------


## **Creating TAB UI**
1. search tab on top search bar
2. click on custom object tab
3. select the custom object you want to use
4. click on save
5. now start entering data in the tab
6. you can simply enter the data in the tab and also able to edit the data too.
