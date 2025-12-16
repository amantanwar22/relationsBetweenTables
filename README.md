# Diagramatic Relation between two tables

This document shows how you can create diagramatic relation between two tables.

## Step 1

- Go to this link - https://dbdiagram.io/home
- Then click on create your diagram button 

## Step 2 

- Now paste your dbml schema in the left side taking below schema for sample:

Table SALES {
  ORDER_ID number [pk]
  CITY string
  AMOUNT number
  ORDER_DATE date
  CUSTOMER_ID number
}

Table CUSTOMERS {
  CUSTOMER_ID number [pk]
  CUSTOMER_NAME string
  CITY string
}

Ref: SALES.CUSTOMER_ID > CUSTOMERS.CUSTOMER_ID

- You can see your diagram showing relations between your tables



