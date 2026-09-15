# E-Commerce Order Management Knowledge Repository

## Objective

This repository contains structured knowledge related to
an E-Commerce Order Management System.

## Entities

- Customers
- Products
- Orders
- Payments
- Shipping

## Relationships

Customer → Places → Order
Order → Contains → Product
Order → Has → Payment
Order → Has → Shipping Status

## Business Rules

1. Successful payment confirms an order.
2. Out-of-stock products cannot be confirmed.
3. Confirmed orders can be processed for shipping.
4. Shipped orders have an In Transit shipping status.

## Purpose

This repository demonstrates how knowledge related to a
real-world business system can be organized and stored
on a cloud-based platform.
