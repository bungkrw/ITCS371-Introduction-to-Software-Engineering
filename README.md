# PROJECT PHASE 2
# 2020-ITCS371-2-JEKCEA

This project is part of ITCS371 Introduction to Software Engineering Course
## Group Members
*   <p>Ekaphat &nbsp&nbsp&nbsp&nbsp&nbsp Seamthong &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6188039</p>
*   <p>Ariya &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Sontrapornpol &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6188041</p>
*   <p>Jirachaya &nbsp&nbsp&nbsp&nbsp Wongsuppakarn &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6188046</p>
*   <p>Kanrawee &nbsp&nbsp&nbsp Chiamsakul &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6188049</p>
*   <p>Ekkawit &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Sangruengkit &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6188122</p>
*   <p>Wanwisa &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Laowsiriwong &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 6188135</p>

<br>

## Table of content

  - [Video Presentation](#video-presentation) 
  - [Revision from the 1st phase](##Revision-from-the-1st-phase) 
  - [Functional Decomposition Diagram](#Functional-Decomposition-Diagram)
  - [Data Flow Diagram--DFD](#Data-Flow-Diagram--DFD)
  - [Level 1](#1-level-1)
  - [Level 2](#2-level-2)
  - [Level 3](#3-level-3)
  - [Level 4](#4-level-4)
  - [Entity Relationship Diagrm--ERD](#Entity-Relationship-Diagrm----ERD)
  - [Mock-up prototype](#Mock---up-prototype)

<br>


---

## Video Presentation

[VDO_URL_Jekcea.txt](/phase-2/VDO_URL_Jekcea.txt) <br/>
OR </br>
[Click here](https://drive.google.com/file/d/1T41PHaIjIPNmu1ut-kJ5ucVDy32feKR4/view?usp=sharing)


---

## Revision from the 1st phase

### Use cases diagram

![Petiverse's Use Case Diagram](/phase-2/Petiverse-Usecase-Diagram.jpg "Petiverse's Use Case Diagram")

1. Rewrite the word “product” to “product / pet” for all use cases: This change has been made because it can cover all of the company’s products.
2. Add “View Customer’s Pets” use case extending to “Manage User Profile” to Customers: This use case has been added because it fulfills the requirements.
3. Delete “View Product” use case from Customers: This use case has been deleted because it is not clear and redundant.
4. Add “Browse” use case to Customers: This use case has been added because it covers more functional requirements for the user.
5. Add “Search” use case to Customers: This use case has been added because it covers more functional requirements for the user.
6. Add “View Delivery Status” use case to Customers: This use case has been added because it covers more functional requirements for the user.
7. Add “Upload Birth Certificate” use case to Farms: This use case has been added because it covers more functional requirements for farms.
8. Add “Update delivery status” use case to Farms: This use case has been added because it covers more functional requirements for farms.
9. Moreover, we have changed the Add to cart use case which used to extend from the “Order Product” use case to be extend from the search use case instated because it makes more sense when the customer search and see the product list, they can add the products to the cart right away.
10. Add “Mange farm info” use case and include 2 use cases;
- Add QC certificate
- Add farm description: This change has been made because it fulfills the requirements.
12. Add “Manage stock details” and include 2 use cases;
- Add Product/Pet details
- Update stock: This change has been made because it fulfills the requirements.
13. Delete “Rate farm” and “Rate Product” use cases: These use cases have been deleted because we will create the new use case to cover these two use cases.
14. Add “Rate farm/product” use case: This use case has been added because it fulfills the requirements.
15. Delete “Add to favorite” extended use cases from “Manage User Profile” use case: This use case has been deleted because it is redundant.
16. Change the link from “Add to cart” extended to “Order Product/Pet” to “Search”
<br>

### Data flow diagram<br>
![Petiverse's DFD level 0](/phase-2/Petiverse-DFD-level0.jpg "Petiverse's DFD level 0")

1. Rewrite the word “product” to “product / pet” for all data flows: This change has been made because it can cover all of the company’s products.
2. Change “Received service” data flow to “Solved problem report” data flow: This change has been made because it is more accurate and correct.
3. Add “veterinarians’ article” data flow from System to Customer: This data flow has been added because it covers more of our functional requirements.
4. Add “Pet information” data flow from System to Customer: This data flow has been added because it covers more of our functional requirements for customers.
5. Add “Pet Birth Certificate” data flow from Farm to System: This data flow has been added because it covers more of our functional requirements for farms.
6. Change “Farm description / Product details” data flow to “Farm description / QC certification” data flow: This change has been made because it is more accurate and correct.
7. Add “Search Keyword” data flow from Customer to System: This data flow has been added because it covers more of our functional requirements.
8. Add “Pet and product list” data flow from System to Customer: This data flow has been added because it covers more of the overall data.
9. Add “Chosen product and pet” data flow from Customer to System: This data flow has been added because it covers more of our functional requirements.
10. Change “Ordered Pet and Product” to “Pet and Product order information” data flow from customer to system: This change has been made because it is more accurate and correct.
11. Add “Location and delivery option” data flow from customer to system: This data flow has been added because it covers more of the overall data in the system.
12. Add “Customer’s message” (consequence) data flow from customer to system to farm: This data flow has been added because it covers more of the flow of the data in our system.
13. Add “Farm’s message” (consequence) data flow from farm to system to customer: This data flow has been added because it covers more of the flow of the data in our system.
14. Change “Problem report” to “Receipt, photo and description of problem” data flow from customer to system: This change has been made because it is more accurate and correct.
15. Separate “Rating submission” to 2 data flows; 
- Veterinarian and article rating
- Product and Farm rating data flows from customer to system and forwarded to veterinarian and farm: This change has been made because it covers all of the flow of the data in our system.
16. Add “Delivery status” farm to system to customer: This data flow has been added because it covers more of our functional requirements.



---

## Functional Decomposition Diagram
![Functional Decompocition](/phase-2/Functional_Decompocition.jpg "Functional Decompocition")


---

## Data Flow Diagram--DFD
### 1. Level 1
#### Complete Diagram
![Petiverse's DFD level 1](/phase-2/Petiverse-DFD-level1.jpg "Petiverse's DFD level 1")
---
#### 1.1 Register
![Register DFD level 1](/phase-2/DFD-LV1/1.Register.png "Register DFD level 1")
---
#### 1.2 Manage customer profile
![Manage Cutomer Profile DFD level 1](/phase-2/DFD-LV1/2.ManageCustomerProfile.png "Manage Cutomer Profile level 1")
---
#### 1.3 View pet birth certificate
![View pet birth certificate DFD level 1](/phase-2/DFD-LV1/3.Viewpetbirthcertificate.png "View pet birth certificate DFD level 1")
---
#### 1.4 Read article
![Read article DFD level 1](/phase-2/DFD-LV1/4.Readarticle.png "Read article DFD level 1")
---
#### 1.5 Browse and search product
![Browse and search product DFD level 1](/phase-2/DFD-LV1/5.Browseandsearchproduct.png "Browse and search product DFD level 1") 
---
#### 1.6 Contact farm
![Contact farm DFD level 1](/phase-2/DFD-LV1/6.Contactfarm.png "Contact farm DFD level 1")
---
#### 1.7 Order Product
![Order Product DFD level 1](/phase-2/DFD-LV1/7.OrderProduct.png "Order Product DFD level 1")
---
#### 1.8 Review product and pet
![Review product and pet DFD level 1](/phase-2/DFD-LV1/8.Reviewproductandpet.png "Review product and pet DFD level 1")
---
#### 1.9 Provide customer service
![Provide customer service DFD level 1](/phase-2/DFD-LV1/9.Providecustomerservice.png "Provide customer service DFD level 1")
---
#### 1.10 Manage farm information
![Manage farm information DFD level 1](/phase-2/DFD-LV1/10.Managefarminformation.png "Manage farm information DFD level 1")
---
#### 1.11 Manage pet and product detail
![Manage pet and product detail DFD level 1](/phase-2/DFD-LV1/11.Managepetandproductdetail.png "Manage pet and product detail DFD level 1") 
---
#### 1.12 Get order
![Get order DFD level 1](/phase-2/DFD-LV1/12.Getorder.png "Get order DFD level 1")
---
#### 1.13 Write article
![Write article DFD level 1](/phase-2/DFD-LV1/13.Writearticle.png "Write article DFD level 1") 
---

---  

### 2. Level 2
#### 2.2 Manage customer profile
![Manage Cutomer Profile DFD level 2](/phase-2/DFD-LV2/2.ManageCustomerProfile.png "Manage Cutomer Profile level 2")
---
#### 2.3 View pet birth certificate
![View pet birth certificate DFD level 2](/phase-2/DFD-LV2/3.ViewPetBirthCertificate.png "View pet birth certificate DFD level 2")
---
#### 2.4 Read article
![Read article DFD level 2](/phase-2/DFD-LV2/4.ReadArticle.png "Read article DFD level 2")
---
#### 2.5 Browse and search product
![Browse and search product DFD level 2](/phase-2/DFD-LV2/5.BrowseSearchproductsandpets.png "Browse and search product DFD level 2") 
---
#### 2.7 Order Product
![Order Product DFD level 2](/phase-2/DFD-LV2/7.OrderProductandpet.png "Order Product DFD level 2")
---
#### 2.8 Review product and pet
![Review product and pet DFD level 2](/phase-2/DFD-LV2/8.Reviewpetproduct.png "Review product and pet DFD level 2")
---
#### 2.9 Provide customer service
![Provide customer service DFD level 2](/phase-2/DFD-LV2/9.ProvideCustomerService.png "Provide customer service DFD level 2")
---
#### 2.10 Manage farm information
![Manage farm information DFD level 2](/phase-2/DFD-LV2/10.ManageFarmInformation.png "Manage farm information DFD level 2")
---
#### 2.11 Manage pet and product detail
![Manage pet and product detail DFD level 2](/phase-2/DFD-LV2/11.Managepetandproductdetail.png "Manage pet and product detail DFD level 2") 
---
#### 2.12 Get order
![Get order DFD level 2](/phase-2/DFD-LV2/12.Getorder.png "Get order DFD level 2")
---
#### 2.13 Write article
![Write article DFD level 2](/phase-2/DFD-LV2/13.WriteArticle.png "Write article DFD level 2") 
---

---

### 3. Level 3
#### 3.7 Order Product
#### 3.7.5 View delivery status
![View delivery status DFD level 3](/phase-2/DFD-LV3-4/7.5Viewdeliverystatus.png "View delivery status DFD level 3")
---

---

### 4. Level 4
#### 4.7 Order Product
#### 4.7.5 View delivery status
#### 4.7.5.1 Get pet delivery status
![Get pet delivery status DFD level 4](/phase-2/DFD-LV3-4/7.5.1Getpetdelivery1.png "Get pet delivery status DFD level 4")
---
#### 4.7.5.2 Get product delivery status
![Get product delivery status DFD level 4](/phase-2/DFD-LV3-4/7.5.2Getproductdelivery2.png "Get product delivery status DFD level 4")
--- 
 
---
 
 ## Mock-up prototype
 
![Prototype2](/phase-2/Prototype_petiverse/Prototype2.jpg "Prototype2")
![Prototype3](/phase-2/Prototype_petiverse/Prototype3.jpg "Prototype3")

---
![Prototype4](/phase-2/Prototype_petiverse/Prototype4.jpg "Prototype4")
![Prototype5](/phase-2/Prototype_petiverse/Prototype5.jpg "Prototype5")


---
![Prototype6](/phase-2/Prototype_petiverse/Prototype6.jpg "Prototype6")
![Prototype7](/phase-2/Prototype_petiverse/Prototype7.jpg "Prototype7")

---
![Prototype8](/phase-2/Prototype_petiverse/Prototype8.jpg "Prototype8")
![Prototype9](/phase-2/Prototype_petiverse/Prototype9.jpg "Prototype9")

---
![Prototype10](/phase-2/Prototype_petiverse/Prototype10.jpg "Prototype10")
![Prototype11](/phase-2/Prototype_petiverse/Prototype11.jpg "Prototype11")

---
![Prototype12](/phase-2/Prototype_petiverse/Prototype12.jpg "Prototype12")
![Prototype13](/phase-2/Prototype_petiverse/Prototype13.jpg "Prototype13")

---
![Prototype14](/phase-2/Prototype_petiverse/Prototype14.jpg "Prototype14")
![Prototype15](/phase-2/Prototype_petiverse/Prototype15.jpg "Prototype15")

---
![Prototype16](/phase-2/Prototype_petiverse/Prototype16.jpg "Prototype16")
![Prototype17](/phase-2/Prototype_petiverse/Prototype17.jpg "Prototype17")
 
 
---

