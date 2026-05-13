1. Difference between Apps, Objects, Records, Fields

Ans:

App: Collection of tools

Object: Database that stores related data

Record: Rows of objects, stores specific data

Fields: Columns, stores data
→ Single piece of information





2. Standard vs Custom Object

Ans:

Standard objects are objects that are included with Salesforce.
Common business objects like account, contact, lead, and opportunity are all standard objects.

Custom objects are objects that you create to store information that’s specific to your company or industry.




3. Formula Fields

Ans:

The powerful tool that gives you control of how your data is displayed.


Example:
We can use formula fields to calculate how many days are left until an opportunity’s close date.




4. Validation Rules

Ans:

Validation rules verify that data entered by users in records meets the standards you specify before they can save it.

It can contain a formula or expression that evaluates the data in one or more fields and returns a value of “True” or “False”.


Example:
You can ensure that all phone number fields contain a specified format or that discounts applied to certain products never exceed a defined percentage.



5. College Data Model

Objects:

College

Department

Program

Course

Section

Student

Faculty etc.


Relationships:

College has many departments

Department offers many programs

Program has many courses

Course has many sections
