# **Understanding object in salesforce**

Let's create a situation , imagine salesforce as a digital office where a company stores information about customer, people
deals and activities

for example :- 
Account - Company/Customer
Contact - Person
Opportunity - Potential Deal or Sale
Lead - Potential customer who hasn't been qualified yet
Case - Customer Problem or Support Request
Campaign - Marketing Campaign



## **Account**
An account represent a company or organization that you have a business relationship with.
For example, A person works at Google and ABC tech wants to buy his corporate training.
So, ABC tech is the account.
We can store data like this :- 
```markdown
**Account Name:** ABC Technologies
**Industry:** Information Technology
**Phone:** 9876543210
**Website:** abc.com
**City:** Jaipur
```
*When we use account?*
- Use account when you need to store information about company/organization/business.



## **Contact**
A contact is a person associated with an account.
For example, A person works at Google and ABC tech wants to buy his corporate training.
So, the person is the contact.
We can store data like this :- 
```markdown
**First Name:** Rahul
**Last Name:** Sharma
**Email:** rahul@abc.com
**Phone:** 9876543210
**Job Title:** HR Manager
**Account:** ABC Technologies
```
*When we use contact?*
- Use contact when you need to store information about person.
- Use contact when you need to store information about customer.



## **Opportunity**
This is one of the most important object for salesforce admins to understand.
An opportunity is a potential deal or sale that you have with a customer.
For example, A person works at Google and ABC tech wants to buy his corporate training.
So, the person is the contact.
We can store data like this :- 
```markdown
**Opportunity Name:** ABC Salesforce Training
**Account:** ABC Technologies
**Amount:** ₹2,00,000
**Close Date:** 30 October 2026
**Stage:** Proposal
```
*When we use opportunity?*
- Use opportunity when you need to store information about potential deal or sale.
- Use opportunity when you need to store information about customer.



## **Account VS Contact VS Opportunity**
ABC Technologies is the account.
Rahul Sharma is the contact.
ABC Salesforce Training is the opportunity.


## **Lead**
A lead is potential customer who hasn't been qualified yet.
For example, someone files your website form:
```markdown
**Name:** Aman
**Email:** aman@gmail.com
**Company:** XYZ Pvt Ltd
**Interested in:** Salesforce Training
```
Right now, you dont know whether Aman is a customer or not.
So, Aman is the lead.

**Lead ---> Account + Contact + Opportunity**

**When to use lead?**
- Use lead when you need to store information about potential customer.
- Use lead when you need to store information about customer.


## **Case**
A case represnt a customer problem, question or support request.
Suppose ABC Tech purchased your salesforce training.
After two weeks rahul says : **We are having issue accessing your training dashboard**
Now we create a case :
```markdown
Case Number: 000123
Subject: Cannot access training dashboard
Status: Open
Priority: High
Account: ABC Technologies
Contact: Rahul Sharma
```
*When we use case?*
- Use case when you need to store information about customer problem, question or support request.
- Use case when you need to store information about customer.


## **Product**
A product represent something your company sells.
Suppose your company sales :-
```markdown
Salesforce admin course
Python course
AI course
Automation course
```
These can be products.
We can store data like this :- 
```markdown
**Product Name:** Salesforce admin course
**Price:** ₹10,000
**Description:** This course covers the basic concepts of salesforce.
```
*When we use product?*
- Use product when you need to store information about product.
- Use product when you need to store information about customer.