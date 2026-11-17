# Inventory and Data Management System

REST API built with Node.js, Express, MongoDB (Mongoose) and dotenv.

## Setup
1. `npm install`
2. Create `.env` with `PORT=5000` and `MONGO_URI=mongodb://127.0.0.1:27017/inventory_db`
3. `npm start`

## API Endpoints
| Method | URL | Purpose |
|---|---|---|
| POST | /api/products | Create product |
| GET | /api/products | Get all (filter, sort, pagination) |
| PUT | /api/products/:id | Update product |
| PATCH | /api/products/:id/stock | Stock adjustment |
| DELETE | /api/products/:id | Delete product |
| GET | /api/products/low-stock | Low-stock report |
| GET | /api/products/summary | Category-wise summary |

## Postman Screenshots

### 1. Get All Products (GET)
![List](Assignment_3/screenshots/list.png)

### 2. Create Product (POST)
![Create](Assignment_3/screenshots/create.png)

### 3. Get All Products after Create (GET)
![List After Create](Assignment_3/screenshots/list-after-create.png)

### 4. Update Product (PUT)
![Update](Assignment_3/screenshots/update.png)

### 5. Stock Adjustment (PATCH)
![Stock](Assignment_3/screenshots/stock.png)

### 6. Low-Stock Report (GET)
![Low Stock](screenshots/low-stock.jpeg)

### 7. Category Summary (GET)
![Summary](Assignment_3/screenshots/low-stock.png)

### 8. Delete Product (DELETE)
![Delete](Assignment_3/screenshots/delete.png)
### 9. Filter + Sort + Pagination (GET)
![Filter Sort](Assignment_3/screenshots/filter-sort.png)
### 10. Get Single Product by ID (GET)
![Get One](Assignment_3/screenshots/get-one.png)
