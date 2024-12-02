**17 Nov, 24**

# Laan Corp USA LLC

### Laan Pos Project

- **Figma link** : (https://www.figma.com/proto/yAK9sB8NU9b1srolEgpLh7/Laan-POS?node-id=1435-8352&t=puUvBJiAyq8E3csx-1&starting-point-node-id=1522%3A8109)
- **Figma link** : (https://www.figma.com/design/yAK9sB8NU9b1srolEgpLh7/Laan-POS?node-id=223-9650&node-type=canvas&t=quwlfA2TFuf9gUqr-0)

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

  - Used Components:

    - [Accordion](https://ui.shadcn.com/docs/components/accordion) :

      ```
      npx shadcn@latest add accordion
      ```

    - [Dialog](https://ui.shadcn.com/docs/components/dialog) :

      ```
      npx shadcn@latest add dialog
      ```

    - [Select](https://ui.shadcn.com/docs/components/select) :

      ```
      npx shadcn@latest add select
      ```

    - [Radio Group](https://ui.shadcn.com/docs/components/radio-group) :

      ```
      npx shadcn@latest add radio-group
      ```

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

### Store Management Module

#### Employees Cashier

- used `React Hook Form` with `Yup` validation

![add new employee](/image/laan-pos/addNewEmployee1.png)
![add new employee](/image/laan-pos/addNewEmployee2.png)
