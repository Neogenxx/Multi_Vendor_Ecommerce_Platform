# Wireframes (Functional, Not Fancy)
---

## 1. Customer Wireframes

### 1.1 Home / Storefront Page

**Purpose:** Discovery + entry into recommendations

```
--------------------------------------------------
LOGO | Search Bar | Login | Cart
--------------------------------------------------
Category Menu (Left / Top Scroll)
- Electronics
- Fashion
- Books
- Home
- Others
--------------------------------------------------
Hero Banner (optional)
--------------------------------------------------
Recommended For You
[ Product Card ] [ Product Card ] [ Product Card ]

Top Selling Products
[ Product Card ] [ Product Card ] [ Product Card ]

Recently Viewed
[ Product Card ] [ Product Card ]
--------------------------------------------------
Footer (About | Contact | Terms)

```

**Key Logic**

- Recommendations block visible only if user is logged in
- Guest users see top-selling products

---

### 1.2 Product Listing Page

```
--------------------------------------------------
Search + Filters
[ Category ] [ Price ] [ Rating ]
--------------------------------------------------
Product Grid
[ Img | Name | Price | Rating ]
[ Img | Name | Price | Rating ]
--------------------------------------------------
Pagination / Infinite Scroll

```

---

### 1.3 Product Detail Page

```
--------------------------------------------------
Product Images (Carousel)
--------------------------------------------------
Product Name
Price | Stock Status
Vendor Name + Rating
--------------------------------------------------
Add to Cart | Buy Now
--------------------------------------------------
Description
--------------------------------------------------
Similar Products (Recommendation)
[ Product ] [ Product ] [ Product ]
--------------------------------------------------
Reviews & Ratings

```

---

### 1.4 Cart & Checkout

```
CartItems
[Product|Qty|Price|Remove]

TotalAmount
CheckoutButton

```

Checkout Flow:

1. Address
2. Payment
3. Confirmation

---

## 2. Vendor Wireframes

### 2.1 Vendor Dashboard

```
--------------------------------------------------
Vendor Name | Logout
--------------------------------------------------
Stats
- Total Products
- Orders Today
- Revenue
--------------------------------------------------
Navigation
- Manage Products
- Orders
- Analytics

```

---

### 2.2 Manage Products

```
AddProductButton
--------------------------------------------------
ProductTable
[Image|Name|Price|Stock|Edit|Delete]

```

Add/Edit Product Form:

- Name
- Category
- Price
- Stock
- Description
- Images

---

### 2.3 Vendor Orders Page

```
OrderID|Product|Qty|Status|Action

```

---

## 3. Admin Wireframes

### 3.1 Admin Dashboard

```
--------------------------------------------------
Admin Panel
--------------------------------------------------
Stats
- Total Users
- Total Vendors
- Total Orders
--------------------------------------------------
Navigation
- Approve Vendors
- Manage Products
- Manage Users

```

---

### 3.2 Vendor Approval Page

```
Vendor Name | Documents | Approve | Reject

```

---