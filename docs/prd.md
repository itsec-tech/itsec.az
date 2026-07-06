# Requirements Document

## 1. Application Overview

**Application Name**: PROSECURITY.AZ

**Description**: A professional security systems e-commerce platform specializing in CCTV cameras, switches, cables, and security equipment. The platform serves both retail customers and wholesale dealers, featuring multi-language support (Azerbaijani, English, Russian), technical calculation tools, and comprehensive management capabilities.

## 2. Users and Usage Scenarios

**Target Users**:
- Retail customers seeking security equipment
- Wholesale dealers and distributors
- System administrators managing the platform

**Core Usage Scenarios**:
- Customers browse and purchase security products online
- Dealers access wholesale pricing and bulk ordering
- Administrators manage products, orders, and content
- Users utilize technical tools for system planning

## 3. Page Structure and Functionality

```
PROSECURITY.AZ
├── Public Website
│   ├── Homepage
│   ├── Product Catalog
│   ├── Product Detail Page
│   ├── Shopping Cart
│   ├── Checkout
│   ├── Search Results
│   ├── Hikvision Smart Technology Center
│   ├── Smart Tools
│   ├── Blog/News
│   ├── Contact Page
│   └── Static Pages
├── User Panel
│   ├── Login/Registration
│   ├── Profile Management
│   ├── Order History
│   ├── Wishlist
│   ├── Quote Requests
│   ├── Messages
│   └── Invoices
├── Dealer Panel
│   ├── Dashboard
│   ├── Bulk Ordering
│   ├── Credit Management
│   ├── Sales Statistics
│   └── Excel Import/Export
└── Admin Panel
    ├── Dashboard
    ├── Product Management
    ├── Order Management
    ├── Customer Management
    ├── CMS Management
    ├── Analytics & Reports
    ├── Technical Tools Management
    ├── Integration Management
    └── Security Settings
```

### 3.1 Public Website

#### 3.1.1 Homepage
- Display sticky header with glassmorphism effect (backdrop-blur, semi-transparent background) on scroll
- Include language switcher UI in header displaying AZ / EN / RU options
- Display gradient hero section with animated subtle mesh/gradient background
- Show hero banner with promotional content using premium typography (display font for headings, Inter for body)
- Show featured products section with product cards featuring hover elevation effect (box-shadow lift)
- Display brand showcase: Hikvision, Dahua, TP-Link, Cisco, Avitel, RVI
- Show animated statistics counter: 2500+ products, 3500+ projects, 5000+ customers, 100% warranty
- Display featured categories section with icons and gradient overlays
- Include prominent \"Become a Dealer\" CTA banner section with dark red gradient background, showcasing dealer benefits: 15% discount, credit line, dedicated support
- Include Hikvision Smart Technology Center showcase section
- Display product grid section
- Display footer with links, social media icons, contact information
- Display contact information: Baku, Azadliq prospekti 143, working hours 09:00-18:00
- Provide WhatsApp order chat button (+994 77 611 77 80)
- Apply dark navy base color (#0A0E1A) with vibrant crimson red (#CC0000) brand color throughout design
- Apply glassmorphism effects on cards (backdrop-blur, semi-transparent backgrounds)

#### 3.1.2 Product Catalog
- Display product categories: IP cameras, analog cameras, DVR/NVR, switches, cables, access control, alarms, smart home
- Show product grid with images, names, prices using cards with hover elevation effect
- Provide filtering and sorting options
- Support pagination

#### 3.1.3 Product Detail Page
- Display product images
- Show product specifications
- Display price
- Provide \"Add to Cart\" button
- Show related products with hover elevation effect

#### 3.1.4 Shopping Cart
- List selected products with quantities
- Display subtotal and total
- Allow quantity adjustment and item removal
- Provide \"Proceed to Checkout\" button

#### 3.1.5 Checkout
- Collect shipping information
- Collect payment information
- Display order summary
- Confirm order submission

#### 3.1.6 Search Results
- Display search results based on user query
- Show product matches with images and prices
- Provide filtering options

#### 3.1.7 Hikvision Smart Technology Center
- Showcase Hikvision technology and solutions
- Display featured Hikvision products
- Provide information about smart technology offerings

#### 3.1.8 Smart Tools
- **Disk Capacity Calculator**: Calculate required HDD storage based on camera count, resolution, recording duration
- **Lens Angle Simulator**: Simulate camera field of view based on lens focal length
- **PoE Calculator**: Calculate PoE power requirements
- **Bandwidth Calculator**: Calculate network bandwidth needs
- **Cable Length Calculator**: Calculate maximum cable distance
- **NVR Channel Selector**: Recommend NVR based on camera count
- **Fiber Distance Calculator**: Calculate fiber optic transmission distance

#### 3.1.9 Blog/News
- Display list of blog posts and news articles
- Show article details with images and content

#### 3.1.10 Contact Page
- Display contact information: address, phone, email, working hours
- Provide contact form for inquiries
- Show map location

#### 3.1.11 Static Pages
- About Us
- Terms and Conditions
- Privacy Policy
- Warranty Information

### 3.2 User Panel

#### 3.2.1 Login/Registration
- User registration with email and password
- User login with credentials
- Password recovery

#### 3.2.2 Profile Management
- View and edit personal information
- Change password
- Manage shipping addresses

#### 3.2.3 Order History
- Display list of past orders
- Show order details and status
- Download invoices in PDF format

#### 3.2.4 Wishlist
- View saved products
- Add products to cart from wishlist
- Remove products from wishlist

#### 3.2.5 Quote Requests
- Submit quote requests for bulk orders
- View quote request status
- Receive quote responses

#### 3.2.6 Messages
- View messages from admin or support
- Send messages to support

#### 3.2.7 Invoices
- View and download invoices in PDF format

### 3.3 Dealer Panel

#### 3.3.1 Dashboard
- Display dealer account overview
- Show credit limit and available credit
- Display recent orders and statistics

#### 3.3.2 Bulk Ordering
- Place bulk orders with special 15% discount
- View wholesale pricing

#### 3.3.3 Credit Management
- View credit limit
- View credit usage and available balance
- Request credit limit increase

#### 3.3.4 Sales Statistics
- View sales reports
- Display order history with filtering

#### 3.3.5 Excel Import/Export
- Import bulk orders via Excel file
- Export order data to Excel

### 3.4 Admin Panel

#### 3.4.1 Dashboard
- Display key metrics: total sales, orders, customers
- Show recent orders and activities
- Display analytics charts

#### 3.4.2 Product Management
- Create, edit, delete products
- Manage product categories
- Set product variants, pricing, stock levels
- Upload product images and documents

#### 3.4.3 Order Management
- View all orders
- Update order statuses
- Generate and send invoices in PDF format
- Process refunds and cancellations

#### 3.4.4 Customer Management
- View customer list
- View customer details and order history
- Approve dealer accounts
- Manage customer credit limits

#### 3.4.5 CMS Management
- Manage sliders and banners
- Create and edit blog posts and news articles
- Manage static pages
- Configure SEO settings: meta tags, sitemap, robots.txt
- Manage media library: images, videos, PDFs, documents
- Configure email and SMS notification templates
- Create and manage promotional campaigns

#### 3.4.6 Analytics & Reports
- View sales analytics: daily, weekly, monthly reports
- View customer analytics
- Export reports

#### 3.4.7 Technical Tools Management
- Configure technical calculator tools
- Update calculation formulas and parameters

#### 3.4.8 Integration Management
- Configure WhatsApp API integration
- Configure email SMTP settings
- Configure SMS gateway
- Configure Google Analytics 4
- Configure Meta Pixel and TikTok Pixel

#### 3.4.9 Security Settings
- Manage user roles and permissions
- Configure two-factor authentication settings
- View audit logs and activity logs
- Configure backup and restore settings
- Manage rate limiting rules

## 4. Business Rules and Logic

### 4.1 User Registration and Authentication
- Users register with email and password
- Email verification required for account activation
- Users can log in with verified credentials
- Support two-factor authentication via Google Authenticator

### 4.2 Dealer Account Approval
- Users can apply for dealer account status
- Admin reviews and approves dealer applications
- Approved dealers gain access to dealer panel with 15% discount
- Dealers receive assigned credit limits

### 4.3 Pricing and Discounts
- Retail customers see standard pricing
- Approved dealers see wholesale pricing with 15% discount
- Promotional campaigns can apply additional discounts

### 4.4 Order Processing
- Customer adds products to cart and proceeds to checkout
- System validates stock availability
- Order is created with pending status
- Admin processes order and updates status: confirmed, shipped, delivered
- Customer receives email/SMS notifications for status changes
- Invoice is generated in PDF format

### 4.5 Credit Management for Dealers
- Dealers have assigned credit limits
- Orders deduct from available credit
- Payments restore credit balance
- Dealers can request credit limit increases

### 4.6 Multi-language Support
- Users select preferred language via language switcher in header: Azerbaijani (AZ), English (EN), Russian (RU)
- Selected language is stored in localStorage for persistence
- LanguageContext provides translation strings for UI labels including: navigation labels, button text, section headings, hero text, cart labels, authentication labels
- All content displays in selected language
- Language preference is saved for logged-in users

### 4.7 Media Upload and Processing
- Supported file types: images, videos, PDF, DOC, XLS, ZIP, APK
- Images are automatically converted to WebP/AVIF formats for optimization
- Files are stored in Supabase Storage

### 4.8 WhatsApp Integration
- Users can initiate WhatsApp chat via button on website
- Chat opens with pre-filled message to +994 77 611 77 80

### 4.9 Mobile App Integration
- Website provides links and information for mobile apps: Hik-Connect, HikCentral Mobile, iVMS-4500, iVMS-4200, Hik-ProConnect, EZVIZ, HiLookVision

### 4.10 Security Measures
- JWT authentication for user sessions
- CSRF protection for form submissions
- XSS prevention for user inputs
- SQL injection protection via parameterized queries
- Rate limiting to prevent abuse
- Audit logs record all admin actions
- Regular backups of database

## 5. Exceptions and Edge Cases

| Scenario | Handling |
|----------|----------|
| User attempts to add out-of-stock product to cart | Display \"Out of Stock\" message, disable \"Add to Cart\" button |
| Dealer order exceeds available credit limit | Display error message, prevent order submission |
| User forgets password | Provide password reset link via email |
| Payment fails during checkout | Display error message, allow user to retry or choose different payment method |
| Admin deletes product with existing orders | Product remains in order history but marked as discontinued |
| User uploads unsupported file type | Display error message with list of supported formats |
| Excel import contains invalid data | Display validation errors, allow user to correct and re-upload |
| Network timeout during order submission | Display error message, allow user to retry |
| User attempts to access dealer panel without approval | Display message indicating pending approval |
| Multiple login attempts with wrong password | Temporarily lock account, require password reset |

## 6. Acceptance Criteria

1. User visits homepage, browses product catalog, selects a product
2. User adds product to cart and proceeds to checkout
3. User completes registration or logs in
4. User enters shipping information and confirms order
5. Order is created and user receives confirmation email
6. Admin views order in admin panel and updates status to shipped
7. User receives shipment notification and can view order status in user panel
8. User downloads invoice in PDF format from order history

## 7. Out of Scope for Current Release

- Live chat support system
- Customer product reviews and ratings
- Loyalty points and rewards program
- Advanced recommendation engine
- Multi-currency support
- Integration with third-party logistics providers
- Mobile native applications (iOS/Android)
- Video tutorials and installation guides
- Augmented reality product preview
- Social media login (Facebook, Google)
- Subscription-based product offerings
- Automated inventory replenishment alerts
- Customer referral program
- Advanced fraud detection system