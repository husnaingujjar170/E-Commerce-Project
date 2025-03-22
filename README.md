# **E-Commerce Desktop Application**

## **Project Overview**
This **E-commerce Desktop Application** is developed using **Windows Forms (WinForms) in C#** with a **SQL database (MySQL)**. The application enables users to browse products, add items to a cart, make purchases, and manage orders efficiently. The system includes **user authentication, product management, cart functionality, and order processing**.

---

## **Features & Functionalities**

### **1. User Authentication & Role Management**
- **Login & Registration**: Users can sign up and log in securely.
- **Admin & Customer Roles**:  
  - **Admin**: Can manage products, orders, and users.
  - **Customer**: Can browse, add to cart, and place orders.

### **2. Product Management**
- Admin can **add, update, and remove products**.
- Product categorization for better organization.
- Search and filter products.

### **3. Shopping Cart & Order Management**
- Customers can **add products to the cart**.
- Update product quantity or remove items.
- Order confirmation and checkout process.

### **4. Payment Processing**
- Option to integrate **payment gateways** (manual or API-based).
- Order tracking (Pending, Completed, Shipped).

### **5. Admin Dashboard**
- Manage **users, products, orders, and categories**.
- View **sales reports and analytics** (Power BI integration).

---

## **Technology Stack**
- **Programming Language**: C#
- **Framework**: Windows Forms (WinForms)
- **Database**: MySQL
- **Backend**: ADO.NET or Entity Framework
- **UI Libraries**: Guna UI, Bunifu UI (optional for modern UI design)

---

## **Installation & Setup**
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/your-repo/ecommerce-winforms.git
   ```
2. **Open the Project in Visual Studio**  
   - Ensure **.NET Framework** is installed.
3. **Setup the Database**  
   - Import the `emp_cust` database in MySQL.
   - Update the **connection string** in the project:
     ```csharp
     string connstring = "server=localhost;uid=root;pwd=root;database=emp_cust";
     ```
4. **Run the Application**  
   - Build and execute from **Visual Studio**.

---

## **Project Screens**
- **Login Screen**
- **Admin Dashboard**
- **Product List & Management**
- **Cart & Checkout**
- **Order Confirmation**

---

## **Future Enhancements**
- **Email Notifications** for order confirmations.
- **Barcode Scanning** for product management.
- **API Integration** for real-time payment and order tracking.
- **WPF Upgrade** for a more modern UI.

