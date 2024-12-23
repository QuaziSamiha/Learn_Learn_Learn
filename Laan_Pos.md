**17 Nov, 24**

# Laan Corp USA LLC

### Laan Pos Project

- **Figma link** : [click here](https://www.figma.com/proto/yAK9sB8NU9b1srolEgpLh7/Laan-POS?node-id=1435-8352&t=puUvBJiAyq8E3csx-1&starting-point-node-id=1522%3A8109)
- **Figma link** : [click here](https://www.figma.com/design/yAK9sB8NU9b1srolEgpLh7/Laan-POS?node-id=223-9650&node-type=canvas&t=quwlfA2TFuf9gUqr-0)

- This project is an `admin panel` of `Pos machine`.
- It's `backend` will be in `Java`.

![pos machine](/image/pos-machine1.png)

- A **POS machine** (`Point of Sale` machine) is a device used by businesses to process payments at the point of sale, where a customer completes a transaction. These machines are a core component of modern retail and service industries. Here's a breakdown:

### Key Features of a POS Machine:

1. **Payment Processing**:  
   POS machines process various payment methods, including:

   - Credit and debit cards (via chip, magnetic stripe, or NFC for contactless payments)
   - Digital wallets (e.g., Apple Pay, Google Pay)
   - Cash transactions in some cases (usually linked to a cash register).

2. **Transaction Records**:  
   POS machines often integrate with software to record and track sales transactions. This helps with inventory management, reporting, and accounting.

3. **Receipts**:  
   They typically print or email receipts for customers.

4. **Integration with Other Systems**:  
   Many POS machines integrate with inventory management, customer relationship management (CRM), and other software systems.

5. **Portability**:  
   Modern POS machines are often wireless and portable, allowing businesses to process payments anywhere, such as at a customer's table in a restaurant or during delivery services.

### Types of POS Machines:

1. **Traditional POS Terminals**:  
   Fixed devices typically found at store counters.

2. **Mobile POS (mPOS)**:  
   Handheld devices or apps on tablets/smartphones that function as POS systems.

3. **Integrated POS Systems**:  
   Systems that combine hardware and software for comprehensive business operations, often including touchscreen interfaces.

4. **Self-Checkout Kiosks**:  
   Specialized POS machines for self-service payments.

##### Usage Scenarios:

- `Retail Stores`: To process customer purchases.
- `Restaurants`: To handle orders and payments at tables.
- `Delivery Services`: For accepting payments at customer locations.
- `Event Ticketing`: For selling tickets and processing payments at venues.

**27 Nov, 24**

### About Project:

- This project contains the following module:
  - Dashboard
    - Reports
    - Store Management
    - Inventory & Financials
    - User Management

#### User Management Module:

- Administrator

**26 Nov, 24**

#### Used Technologies

- [Shadcn/ui](https://ui.shadcn.com/docs)

**25 Nov, 24**

### Dashboard --> Administrator (http://localhost:3000/administrator)

- React hook form implement for add new user

![admin1](/image/laan-pos/addNewUser1.png)
![admin2](/image/laan-pos/addNewUser2.png)
form filled up
![admin2](/image/laan-pos/addNewUser3.png)

#### `Meeting` (About Laan POS):

- this project will contain
  - `super admin`
  - `admin`
  - `employees` (department wise)
  - a `template` for producing `receipt` and `bar code`
  - `drag & drop` page

**26 Nov, 24**

### Administrator

- `shadcn ui` : it's not a component library, it is a collection of reusabale components

![admin3](/image/laan-pos/administrator3.png)
![admin4](/image/laan-pos/administrator1.png)
![admin5](/image/laan-pos/administrator2.png)

**1 Dec, 24**

## Store Management Module

#### Employees Cashier

- used `React Hook Form` with `Yup` validation

![add new employee](/image/laan-pos/addNewEmployee1.png)
![add new employee](/image/laan-pos/addNewEmployee2.png)

**19 Dec, 24**

#### Tax Setup

![tax setup](/image/laan-pos/tax-setup1.PNG)
![tax setup](/image/laan-pos/tax-setup2.PNG)
![tax setup](/image/laan-pos/tax-setup3.PNG)
![tax setup](/image/laan-pos/tax-setup4.PNG)

**User Interface Features**

  - Pagination for navigating between tax records.
  - Search functionality to quickly locate a record.
  - Options to export data to PDF or CSV formats. **Confusing Section**
  - Form for adding new tax records via a New Tax Setup button

**Functionality**


**12 Dec, 24 & 15 Dec, 24**

### Promotion Section: `Store Management Module`

- It will contain `3 tabs` such as
  - `Promotional Product List`
  - `Mix & Match Promotion`
  - `Combination Promotion`

#### `Promotional Product List` Tab

- A table will be available. All Promotional Product lists will be shown on that table.
- This table will contain the following columns:
  - Name (`Promotion Name`)
  - POS ID
  - List Type (either `Product` or `Department`)
  - List size
  - Action (it will contain `Delete` option)
- On the table header there will a button 'New Promotion Product' to add new promotion for a product. After clicking this button a
  modal will open. This modal contains a form that will contain the following field:
  - 1. Name (promotion name)
  - 2. select list (you have to select `Product List` or `Department List`)
  - 3.
    - if you select `Product List`, then
      - you will get options for selection by `Product Name` or `SKU (Stock Keeping Unit)` (you have to select `at least 1 product` but you can select `multiple product`)
      - After selecting products name or SKU total no of selected product will be shown on below `Current list size` and
        a list will be shown like table , it will contain `SKU`, `Name(Product name)` and `Action(delete)` as columns.
    - if you select `Department List`, then
      - you will get options for selection by `Department` (you have to select `at least 1 department` but you can select `multiple department`)
      - After selecting departments by name total no of selected department will be shown on below `Current list size` and
        a list will be shown like table , it will contain `POS ID`, `Name(Department name)` and `Remove` as columns.

#### `Mix & Match Promotion` Tab

- A table will be available. All `Mix and Match List` will be shown on this table.
- This table will contain the following columns:
  - Name
  - POS ID
  - Store
  - Start Day/Time
  - End Day/Time
  - Days of week available
  - List Used
  - Price Breaks
  - Action (Delete)
- A button `New Mix & Match Promotion`. After clicking a modal will open. This modal will contain a form.
  This form will contain the following fields:
  - List to apply promotion (`Selection Field` - only on `list` can be selected from here)

**12 Dec, 24**

# General Knowledge:

## Promotion:

### Imagine This Scenario:

You run a **coffee shop** in the USA. You sell coffee, pastries, and sandwiches. You want more people to visit your shop and buy your products. To achieve this, you decide to **promote your products**.

---

### Example of Product Promotion:

#### 1. **Offer a Discount:**

You announce:  
**"Buy 1 coffee, get the 2nd coffee 50% off."**

- **Why this works:**  
  People love discounts. A customer who was planning to buy one coffee might now buy two because they feel they’re saving money. This also encourages them to bring a friend, increasing foot traffic.

---

#### 2. **Create a Limited-Time Deal:**

You say:  
**"Free pastry with any coffee purchase—this weekend only!"**

- **Why this works:**  
  The limited time creates urgency—customers think, _"I don’t want to miss this deal!"_  
  You might sell more coffee because the free pastry makes it feel like a better deal.

---

#### 3. **Loyalty Program:**

You introduce:  
**"Buy 5 coffees, get 1 free."**

- **Why this works:**  
  People like rewards. Customers will keep coming back to your shop instead of going to another coffee shop because they want to earn their free coffee.

---

#### 4. **Social Media Promotion:**

You post on Instagram:  
**"Share a picture of your coffee and tag us for a chance to win a $10 gift card!"**

- **Why this works:**  
  Customers share your business with their friends for free, giving you more exposure without spending on ads.

---

### Summary of the Strategy:

1. You use discounts, limited-time offers, and rewards to attract more customers.
2. You make your products feel more valuable and special.
3. Your goal is to increase sales and bring customers back repeatedly.

## Retail Store

A **retail store** is a business that sells products or goods directly to customers for their personal use. Retail stores are the final point in the supply chain where goods move from manufacturers or wholesalers to individual buyers.

### Key Characteristics:

1. **Direct to Consumer:** Retail stores serve customers who want to purchase items for personal or household use.
2. **Physical or Online:** They can be physical locations (like Walmart) or online platforms (like Amazon).
3. **Wide Variety of Products:** They often sell a range of items, from groceries and clothing to electronics and furniture.

---

### Types of Retail Stores:

1. **Department Stores:**  
   Large stores with sections for different types of products.  
   _Example:_ Macy’s, Kohl’s.

2. **Supermarkets:**  
   Stores that focus on food and household items.  
   _Example:_ Walmart, Kroger.

3. **Specialty Stores:**  
   Focus on specific products like shoes, books, or electronics.  
   _Example:_ Foot Locker (shoes), Best Buy (electronics).

4. **Convenience Stores:**  
   Small stores offering essential items, usually open late.  
   _Example:_ 7-Eleven, gas station mini-marts.

5. **Online Retailers:**  
   Websites or apps where customers shop online.  
   _Example:_ Amazon, eBay.

# SKU (Stock Keeping Unit)

**SKU** stands for **Stock Keeping Unit**, a unique identifier assigned to each product in a store or inventory system. It helps businesses track products, manage inventory, and streamline sales processes.

---

### Key Features of an SKU:

1. **Unique Identifier:** Each product and its variations (like size, color, or model) gets a distinct SKU.
2. **Customizable Format:** SKUs are usually alphanumeric codes created by the business. For example:
   - **"SHRT-BLU-MED"** (for a medium blue shirt).
   - **"ELEC-TV-55IN"** (for a 55-inch television).
3. **Internal Use:** SKUs are mainly for internal tracking and aren’t standardized like barcodes or UPCs (Universal Product Codes).

---

### How SKUs Work:

- A **clothing retailer** sells shirts in different colors and sizes:
  - A **red shirt, size small** might have the SKU **"SH-RED-S"**.
  - A **blue shirt, size medium** might have the SKU **"SH-BLU-M"**.
- When a sale happens, the POS system uses the SKU to:
  1. Deduct the product from inventory.
  2. Track which product is selling well.

---

### Why SKUs Are Important:

1. **Inventory Management:**  
   SKUs make it easy to track how many units of each product are in stock.  
   _Example:_ A store can see they have 10 blue shirts in stock but are out of red ones.

2. **Sales Analysis:**  
   Businesses can analyze which SKUs sell best and adjust their stock or promotions.

3. **Customer Service:**  
   If a customer wants a specific item, the staff can quickly find it using the SKU.

---

### Example:

A grocery store sells apples in different types and weights:

- **SKU001:** Gala Apples, 1 lb.
- **SKU002:** Fuji Apples, 1 lb.
- **SKU003:** Gala Apples, 2 lbs.

By tracking SKUs, the store knows how many Gala apples (1 lb) are left or if they need to reorder Fuji apples.

---

## Inventory

- The term "inventory" refers to the collection of goods, materials, or products that a business keeps on hand for the purpose of production, resale, or usage. The meaning can vary slightly depending on the context
