# Information Gathering 


>Gathering all components of the database and losely organizing them

### Devices
- printer
- monitor
- Server
- laptop

#### Device Type
- ID
- Type


#### Printer
- Device ID
- Mac-Adress
- Serial-Number
- Brand
- Workspace ID
- Cost
- Buy date

#### Monitor
- Device ID
- Workspace ID
- Serial-Number
- Model
- Buy date

##### Monitor_Model
- Size
- Resolution
- Brand
- Cost
- Energy Efficiency

#### Laptop
- Device ID
- Mac-Adress
- Serial-Number
- Buy date
- User
- Model

##### Model_Laptop
- Size
- Resolution
- CPU
- RAM
- Brand
- Cost
- Energy Efficiency

#### Server
- Device ID
- Mac-Adress
- Serial-Number
- Place
- Buy date

##### Server_Model
- CPU
- RAM
- Brand
- Cost
- Energy Efficiency

### Maintenence
- Device ID
- Date

### Workspace
- Room_ID

### Room
- Room ID
- Room number
- Department_ID

### Branch
- Employes
- Location
- Type
-

### Department
- Employes
- Locaation_ID
- Room_ID

### Location
- Location_ID
- City
- Adress

### Employes
- Lastname
- Firstname
- EMail
- Laptop_ID
- Department_ID
- Branch_ID


### Workshop
- Name
- Customer_ID
- Department_ID
- Room_ID
- Teacher

### Teacher
- Employe_ID
- Workshop_ID


### Customer
- First Name
- Last Name
- E-Mail

### Compnay
- Customer_ID
- Compnay Name

### Orders
- Customer_ID
- Order Date
- Fulfilment Date
- Invoice_ID

### Invoice
- Invoice number
- Price
- Customer_ID
