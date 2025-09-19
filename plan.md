# Live Bid System - Development Plan

## 1. Project Overview
**Live Bid System** is a **real-time auction platform** where:
- Only **Admin** can register/login, create bidders, add auctions, and top-up balances.
- **Bidders** are created by Admin and can participate in live auctions.
- The system uses **Node.js, Express, REST APIs, Socket.io, MySQL, and MongoDB**.
- Minimal frontend (3 pages): Admin panel + Auction list + Auction room.


## 2. Roles
### Admin
- Register & login
- Create bidders
- Create auctions/products
- Add balance to bidders
- View auctions and bidders
### Bidder
- Cannot register/login independently
- View active auctions
- Place bids if balance ≥ bid
- Receive real-time updates via Socket.io