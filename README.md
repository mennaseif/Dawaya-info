## Writing ERD For Example : Pharmacy

 **Dawaya**

**This application will help users easily find nearby pharmacies that have the medicines they need.**

- **Each pharmacy** that is recorded at Dawaya has an ID (unique) , Profile photo may be a logo, Name, Email.

A pharmacy can employ multiple pharmacists, have multiple inventory items and multiple reviews.

- **Each Pharmacist** that is recorded at Dawaya has an Pharmacist ID (unique), Full name , Email , Password and License Number.

Each pharmacist works at only one pharmacy and manage branch’s e**nventory**.

- **Each user** that is recorded at Dawaya has an ID (unique) , Full name , Email , Password and a Phone Number address(city, Streat name, locationURL).

A user can leave one review to every pharmacy **and** can add more than one pharmacy to his favorite list

- **Enventory** keeps track of the quantity and details of medicines at different pharmacies.

Inventory ID (unique), update date and Quantity.

Each inventory record refers to many medicines and belongs to one pharmacy.

- **Each Branch** recorded at a pharmacy has an ID (unique), pharmacy name, address(city, ST, locationURL), licence number, may have a photos of the place , contact numbers, opening houres, Drs name and **Enventory** record

**Each Branch can have a multipule pharmacist but at least one the branch**

- **Each Medicine** that is recorded at Dawaya has a Medicine ID(unique) , Name , description, Dosage, Manufacturer ,category , Price and The Available Quantity .

A medicine can be listed in multiple inventory records at different pharmacies and belongs to one category.

- **Review** Requests user feedback on pharmacies.

Review ID (unique), Rating (1-5) , Comment and Review Date.

Each review is written by one user and for one

pharmacy.

## ERD Diagram

[ERD.drawio](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/53ed3615-c27a-4429-8e64-b40333dfdf1a/ERD.drawio)

![ERD.svg](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/22962567-09ba-4991-912b-d0ef0f5f869c/ERD.svg)

![ERD.svg](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/7433ad7c-62a5-431e-9cfc-4ad18e42a861/ERD.svg)

## Mapping

[Mapping.drawio](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/f9433605-617c-4f0e-b2ee-e06635c2f14d/Mapping.drawio)

![Mapping.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/bfd16ec4-61ea-4a9a-b7e4-549ef7ce16ba/Mapping.png)

## Schema

live Schema: ‣

![Schema.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/185d6250-e8b2-49ff-bd71-d983e5d22d1c/Schema.png)

![schemaWithBackground.svg](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/a4fe1c5c-3439-4e6d-8fd6-eedaae69a481/schemaWithBackground.svg)

![Schema.svg](https://prod-files-secure.s3.us-west-2.amazonaws.com/36c777e8-f9c6-4a80-87bd-4f240912062d/0e522429-54ea-496a-bd8d-84b744acbe63/Schema.svg)