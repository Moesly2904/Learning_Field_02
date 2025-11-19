# Information Gathering

>Gathering all components of the database and loosely organizing them

## Devices

- printer
- monitor
- Server
- laptop

### Device Type

- ID
- Type

## List of Device Types

### Printer

- Device ID
- Mac-Address
- Serial-Number
- Workspace ID
- Buy date

#### Printer_Model

- Brand
- Cost
- Name

### Monitor

- Device ID
- Workspace ID
- Serial-Number
- Model
- Buy date

#### Monitor_Model

- Size
- Resolution
- Brand
- Cost
- Energy Efficiency

### Laptop

- Device ID
- Mac-Address
- Serial-Number
- Buy date
- User
- Model

#### Model_Laptop

- Size
- Resolution
- CPU
- RAM
- Brand
- Cost
- Energy Efficiency

### Server

- Device ID
- Mac-Address
- Serial-Number
- Place
- Buy date

#### Server_Model

- CPU
- RAM
- Brand
- Cost
- Energy Efficiency

---

### Maintenance

- Device ID
- Date

### Workspace

- Room_ID

### Room

- Room ID
- Room number

### Location

- Location_ID
- City
- Address

### Employees

- Last name
- First name
- EMail
- Laptop_ID
- Department_ID

---

## Unneeded

### Workshop

- Name
- Customer_ID
- Department_ID
- Room_ID
- Teacher

### Teacher

- Employee_ID
- Workshop_ID

### Customer

- First Name
- Last Name
- E-Mail

### Company

- Customer_ID
- Company Name

### Orders

- Customer_ID
- Order Date
- Fulfillment Date
- Invoice_ID

### Invoice

- Invoice number
- Price
- Customer_ID

### Branch

- Employees
- Location
- Type

### Department

- Employees
- Location_ID
- Room_ID
