# Stock Outline

## Project Description
StockCheck is an Android mobile application designed to provide accurate, real-time inventory management.  
It aims to solve the common problem of mismatched recorded against actual inventory for businesses of all sizes, including retail stores, warehouses, distribution centers, and small businesses.

## Problem Addressing
The main problem our app addresses is:  
- Businesses often find that recorded stock levels do not match what is physically available — “it says we have it, but we don’t.”  
- This can lead to lost revenue, excess inventory, labor waste, operational mistakes, and dissatisfied employees or customers.  
- Small businesses, retailers, warehouses, distribution centers, and their employees/managers are affected.  

By solving this problem, StockCheck will provide real-time tracking, automated discrepancy notifications, and cloud-based syncing, helping businesses reduce financial losses, improve efficiency, and make better inventory decisions.

## Platform
The app will be developed for:  
- Android mobile devices 
- Windows Desktop 
- Reason for platform choice: Android allows on-the-floor inventory management and barcode scanning, while desktop provides a detailed view for managers and reporting. This combination balances mobility and administrative flexibility.

## Front-End / Back-End Support
Front-End:
- Flutter, along with HTML, CSS, and JavaScript for layout, styling, and interactivity  
- Features include quick QR/barcode scanning, real-time dashboards, and inventory listings  

Back-End: 
- Firebase Cloud Database for real-time synchronization  
- APIs connect the front-end to the database, analytics tools, and automated alerts  
- Secure cloud storage keeps track of past records, reports, and user activity logs  

## Functionality
Key features include:  
- User login system with manager-controlled access  
- Customizable employee permissions  
- Real-time inventory tracking across multiple locations  
- Fast QR code and barcode scanning 
- Stock arrival and low stock notifications  
- Management error warnings 
- Shipment or return batch updates  
- Item categorization and inventory history monitoring  
- Order and supplier management

## Design 
The design approach includes:  
- Main screens: Home, Menu, Inventory List, Scan, Item Details, Alerts & Notifications, Reports, Settings, Supplier/Order Management, Multi-Location View  
- Wireframes will be created using **Figma**  
- Focus on a **user-friendly, intuitive, and modern interface** for quick navigation and actionable insights

## Updates
Since the first outline and wireframes back in Module 1, I made several updates to improve how the app would actually feel for a real user. One of the biggest changes I added was a logout button on every main page instead of only keeping it inside settings, because I realized users might need to log out quickly if they are sharing devices at work or ending a shift. I also expanded the Settings and Personal Information area so users can now add extra details like their social media or contact info, which makes the profile feel more complete instead of just a basic name and email. Another change I included was an edit button in the personal information section so users are not stuck with whatever they typed the first time and can easily update things later. I also thought it would be useful to allow users to take or upload a profile picture, because it adds personalization and helps managers quickly recognize employees in larger businesses. These changes were made to make the app more user-friendly, flexible, and realistic for everyday use instead of just being a simple inventory tool on paper.

## History
- Module 1 
Created the original StockCheck idea and main purpose (inventory tracking)
Chose Android and Windows as the platforms
Built first wireframes in Figma
Home/Login screen included logo, username, password, forgot password, and login button
Home screen had scan item, inventory list, reports, alerts, and footer navigation
Scan screen had large barcode scanner and scan button
Inventory list screen included search bar, filter button, long item list, and + add button
Settings screen included account, personal info, toggles, and logout button

- Module 5 
Added logout button to everyday pages, not just settings
Expanded personal information section to include social media/contact space
Added edit button for personal information so users can change details anytime
Added option for profile picture/photo upload
Improved overall usability ideas based on how real employees might use the app daily
Focused more on personalization and quick access features instead of only inventory functions

