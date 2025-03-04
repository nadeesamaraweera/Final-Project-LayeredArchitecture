# **🧵 Coir Management System**

## **📌 Project Overview**
The **Coir Management System** is my first semester final project, developed as a **standalone JavaFX application** following a **Layered Architecture**. It is designed to streamline the management of customer orders, suppliers, employees, raw materials, and deliveries within a coir-related business. This system provides a structured and efficient approach to handling business operations.

## **🛠️ Tech Stack**
- **☕ Java (JavaFX)** – Frontend user interface  
- **💬 MySQL** – Database management  
- **🏞️ FXML** – UI design with JavaFX  
- **🔗 JDBC** – Database connectivity  
- **💶 Maven** – Dependency management  

## **📂 Project Structure**
### **🔙 Layered Architecture**
The project follows a **Layered Architecture**, ensuring modularity and separation of concerns.

#### **🏢 Presentation Layer (View Layer)**
- **FXML Views**: Contains the user interface components.
- **Controllers**: Handle user interactions and send data to the service layer.

#### **💼 Business Logic Layer (Service Layer)**
- Contains business logic and coordinates data flow between the presentation and data access layers.
- **Validation** and **data processing** before calling DAO methods.

#### **📋 Data Access Layer (DAO Layer)**
- Handles database CRUD operations.
- Uses JDBC for database connectivity.

#### **📦 Entity Layer**
- Represents database tables as Java classes.
- Uses DTOs (Data Transfer Objects) to ensure data encapsulation.

#### **💾 Database Layer**
- MySQL database that stores all business-related data.
- **SQL Scripts** to manage tables and relationships.

### **💻 Frontend (FXML)**
The `resources/view/` directory contains the FXML files defining UI components:
- **🏠 dashboardForm.fxml** – Main dashboard  
- **👤 customerForm.fxml** – Customer management  
- **🚚 deliveryForm.fxml** – Delivery tracking  
- **📧 emailForm.fxml** – Email notifications  
- **🧑‍💼 employeeForm.fxml** – Employee management  
- **🔑 forgotPasswordForm.fxml** – Password recovery  
- **📦 itemForm.fxml** – Item management  
- **🔒 loginPageForm.fxml** – User authentication  
- **📊 materialStockForm.fxml** – Raw material inventory  
- **🔄 otpForm.fxml** – OTP verification  
- **🛒 placeOrderForm.fxml** – Order placement  
- **🌾 rawMaterialForm.fxml** – Raw material management  
- **🔄 resetPasswordForm.fxml** – Password reset  
- **🏭 supplierForm.fxml** – Supplier management  

## **🚀 How to Run the Project**
1. **📥 Clone the repository**  
   ```sh
   git clone <https://github.com/nadeesamaraweera/coir_related_products_management_system.git>
   ```
2. **🛠️ Setup MySQL Database**  
   - Import the SQL script from the `sql/` directory.
   - Update the database connection details in `DbConnection.java`.

3. **▶️ Run the Application**  
   - Open the project in an IDE (**IntelliJ IDEA** or **Eclipse**).
   - Run `AppInitializer.main()`.

## **✨ Features**
- **👥 Customer & Employee Management** – Add, update, delete, and view records.  
- **📦 Order & Supplier Tracking** – Maintain order history and supplier details.  
- **🚛 Delivery Monitoring** – Track deliveries efficiently.  
- **📊 Material Stock Management** – Maintain inventory of raw materials.  
- **🔐 User Authentication** – Login, password reset, OTP verification.  
- **📁 Report Generation** – Generate reports using JasperReports.  
---

## **📜 License**
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

