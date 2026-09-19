# **Salesforce**
Salesforce is a powerful CRM or customer relationship management platform that helps business streamline sales, marketing and automation. Whether you are a student exploring new technologies or a professional looking to enhance your business processes, Salesforce has something to offer.

---------------------

## **CRM**
Think of CRM as a digital relationship manager for your business.
CRM isn't just storing data, it's helping a company manage customer relationships and business process around that data.
Salesforce stores and oraganize this information.
suppose theres a student in college and he wants to manage his relationship with the college.
he can do this by creating a student record in salesforce.
this record will contain information about the student like his name, age, address, phone number, email, etc.
```markdown
Name: Rahul
Email: rahul@example.com
Phone: 98XXXXXXXX
Interested Course: Python
Lead Source: Website
Status: Interested
Counsellor: Amit
Last Contact: 8 Sept
```


---------------------

## **Salesforce Org**
This is very important term, to understand while learning Salesforce.
A salesforce org or organization is basically your company's salesforce enviorment.
Think of it as a single instance of salesforce, where you can store and manage your data.
For example a collge's salesforce org will be like :
```markdown
STUDENTS
COURSES
REPORTS
PROGRAMS
LEADS
DASHBOARDS
SECURITY
EXAMS
```
When we create a salesforce org, we are creating a new instance of salesforce, where we can store and manage our data.

---------------------


## **Salesforce Admin**
A salesforce adminstrator is the person who configures and maintains and supports for an organization.
Think of it as , the person who makes salesforce work according to the company's needs.
For example : 
```markdown
Our sales employees need to enter customer information, managers should see everyone's data, and whenever a new high-value opportunity is created, the manager should receive an alert.
```
The admin figure out how to configure salesforce to meet the company's needs.

---------------------


### **Saleforce Admin Responsibilities**
1. Admin work with user
* Admin can create user and manage user.

2. Secuirty
* Admin can configure security settings to protect data and prevent unauthorized access.

3. Configuration
* Can create and modify Objects, Fields, Page layouts, Apps and Record pages

4. Reports and Dashboards 
* Admin can create and manage reports and dashboards to provide insights into the data.

5. TroubleShooting 
* Admin can troubleshoot and resolve any issues or errors that arise in salesforce.

---------------------

## **Salessforce Ecosystem**
Salesforce isn't just a single product, its an ecosystem of products that work together to provide a complete solution for CRM.
Think of it as  : 
```markdown
                    Salesforce
                        │
        ┌───────────────┼────────────────┐
        ↓               ↓                ↓
      Sales           Service          Marketing
        │               │                │
        └───────────────┼────────────────┘
                        ↓
                  Salesforce Platform
                        │
              ┌─────────┼─────────┐
              ↓         ↓         ↓
            Flow      Apex       LWC
```
It does include : 
* Salesforce Platform
* Salesforce CRM
* Salesforce Marketing Cloud
* Salesforce Service Cloud
* Salesforce App Cloud

---------------------

## **Salesforce Platform**
This is the core of salesforce, where you can store and manage your data.
It provides the basic features and tools to build and deploy applications on salesforce.
The platform provide capabilities for following : 
* Data storage
* Objects
* Secuirty
* User Management
* Automation
* Applications
* APIs
* Reports
* Dashboards

Think of it like a foundation, on where you build your salesforce applications.
```markdown
              Salesforce Applications
        ┌────────┬────────┬──────────┐
        │ Sales  │Service │Marketing │
        └────────┴────────┴──────────┘
                    ↓
            Salesforce Platform
                    ↓
        Data + Security + Automation
```

----------------------

## **Salesforce Navigation**
When you open salesforce, you are greeted with a navigation bar, which contains the following sections : 
* Home
* Objects
* Reports
* Dashboards
* Settings
* Help

--------------------

## **App Launcher**
The app launcher helps user access salesforce applications, feature and tools or item available to them.
For reference think of it as a door, which leads to the different rooms of salesforce.
```markdown
              App Launcher
        ┌────────┬────────┬──────────┐
        │ Sales  │Service │Marketing │
        └────────┴────────┴──────────┘
                    ↓
            Salesforce Platform
                    ↓
        Data + Security + Automation
```

--------------------------------


## **Data Types in Salesforce**
Salesforce supports a wide range of data types to store and manage information.
It determines how data is stored and processed in salesforce.
Each field in salesforce has a specific data type and selecting correct one is crucial for 
* efficient data storage
* accurate data processing
* improved user experience
* enhanced security


Few Data types are as follows :
* Text
* Number
* Date
* Time
* DateTime
* Boolean
* Picklist
* Multi-Select Picklist
* Lookup
* Reference
* Formula
* Custom
* Long Text
* Rich Text
* HTML
* Image
* File
* URL
* Email
* Phone
* Currency
* Decimal
* Integer


---------------------

## **Common Field and Data Types Exaplained**
1. **Auto Number** : 
* Automatically generate unique numbers for records
* format can be customized
* useful for sequential IDs like Invoice number etc

2. **Formula** :
* read only field
* calculates values using logic and other fields
* Ex : calculate discount on a price

3. **Text** : 
* Stores short alphanumeric text up to 255 characters
* useful for storing short paragraphs or notes

4. **Text Area** : 
* Stores longer text up to 255,000 characters
* useful for storing detailed descriptions or comments

5. **Text Area Long** :
* Stores even longer text up to 255,000 characters
* useful for storing detailed descriptions or comments

6. **Text Area Rich** :
* Stores formatted text with rich text features
* Allow bold, italic, underline, and other formatting options
* useful for storing detailed descriptions or comments

7. **Number** :
* Stores numeric values
* Supports decimal precision
* Ideal for storing quantities or scores

8. **Picklist** :
* Drop-down field with predefined values
* 1Ensures consistent inputs for fields like Status or Category

9. **Checkbox** :
* Boolean field: true/false
* Great for binary choices like Active/Inactive

10. **Currency** :
* Stores monetary values
* Automatically formats based on locale and currency type
* Useful for budgets, pricing, and financial transactions


---------------------


