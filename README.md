# JSCApp

Ticket and Foodcourt Point Of Sale

### Ticket POS (Touchscreen Version)

- Admin Dashboard (Single Page and Admin Login)
	- Server Status : Online/Offline Red or Green Dot (Pings Number)
	- Add/Edit/Save Ticket Price
	- Add/Edit/Save Ticket Category
		- Ticket Subcategory
	- View Ticket Sales Record
	- Edit/Add/Remove Sales
	- Export Sales Log to XLS
	- Config Ticket Points
		- Gates Name
		- Add/Edit/Save Customer Service Contact Number
		- Add/Edit/Save Cashier Name and 5 Digit Pin
		- Terms & Conditions (Text Area 250Characters)
		- Logo (40x50px)

- Create Ticket (Single Page and Cashier Login)
	- Server Status : Online/Offline (Pings Number)
	- Ticket ID (for barcode generator)
	- Ticket Category (Dropdown)
	- Ticket Amount (Modal Number)
	- Print Tickets (Using Thermal Printer, print multiplying as ticket amount)
		- Header (logo)
		- Ticket Category (Bold Capitalized maximum 40px width)
			- Ticket Subcategory 
		- Date/Time
		- Ticket Barcode Lines
		- Footer Line
		- Terms & Conditions.
		- Autocut line (if Thermal Print doesn't have auto cut)

### Foodcourt Cashier (Touchscreen Version)

- Foodcourt Admin Dashboard (Single Page and Admin Login)
	- Server Status : Online/Offline Red or Green Dot (Pings Number)
	- Config Foodcourt
		- Add/Edit/Save Foodcourt Name
		- Add/Edit/Save Customer Service Contact Number
		- Add/Edit/Save Cashier Name and 5 Digit Pin
		- Terms & Conditions (Text Area 250Characters)
		- Logo (40x50px)

	- Add New Merchant (Autogenerated 4 Digits Merchant Code)
	- Add New Products and Price (based on merchants)
	- Add/Edit/Remove Products/Price/Merchant
	- View/Edit/Print Sales Log

- Sales Page/Cashier (Single Page and Cashier Login)
	- Server Status : Online/Offline Red or Green Dot (Pings Number)
	- Input Merchant Code (auto complete ajax)
	- Input Product Code/Name (auto complete ajax)
	- Price Amount and Sales Details
	- Print Note (Using Thermal Printer, print 2 times)
		- Header (logo)
		- Foodcourt Name (Bold Capitalized maximum 40px width)
		- Date/Time
		- Purchasing Item Detail with Qty and Price
		- Payment Status: (PAID/UNPAID)
		- Footer Line
		- Terms & Conditions.(Text Area 250Characters)
		- Autocut line (if Thermal Print doesn't have auto cut)

		
## Alert System Bar
- Koneksi Server Gangguan - Red Bar
- Pembelian Berhasil - Green Bar
- Tiket Gagal Dicetak - Yellow Bar
- Pembayaran Diterima - Blue Bar

## Page Header/Menu Navbar
- Logo
- Logged in Username
- Login/Logout
- Page Name

## Side Menu
- Ticket POS
	- Admin Dashboard
	- Create Ticket
	- System/Error Log
	
- Foodcourt POS
	- Admin Dashboard
	- Sales Page/Cashier