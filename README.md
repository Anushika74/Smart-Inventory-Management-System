SMART INVENTORY MANAGEMENT SYSTEM WITH AI-BASED BUSINESS INSIGHTS

A complete Java Web Application for a supermarket / retail shop that manages
products, stock, and sales — enhanced with four AI/ML-powered features for
smart business decisions.

Module: Java Web Application Development — Final Assignment


FEATURES

Part 1 — Core Inventory System

  - User Authentication — login / logout with roles (ADMIN / STAFF)
  - Product Management — add / update / delete / search products
  - Inventory Management — add stock, update quantity, view stock,
    low-stock alerts
  - Sales Management — record sales, generate bills/invoices, sales history
  - Reports — daily sales, monthly sales, product stock report

Part 2 — AI / ML Enhancement

  - Smart Restock Prediction — predicts days-to-stockout and recommended
    restock quantity from sales velocity and historical demand (linear
    regression)
  - Fast & Slow Moving Product Analysis — classifies products as Fast /
    Slow / Dead stock (with charts)
  - Sales Trend Analysis — analyzes daily / weekly / monthly sales and
    forecasts the next period
  - Intelligent Alerts — low stock, overstock, sudden sales drops, and
    expiring products

Required pages (all included):
Login, Dashboard, Product Management, Inventory Management, Sales
Management, Reports, AI Insights Dashboard, Prediction & Analytics

Required charts (Chart.js):
Sales Trend, Product Performance, Revenue Analysis, AI Prediction


ARCHITECTURE

The system is built in layers. The browser runs Bootstrap 5 and Chart.js
for the interface. Behind that sits the Java web app, built with Spring
Boot 3, Spring MVC, Thymeleaf, and Spring Security. This layer talks to a
MySQL 8 database through Spring Data JPA and Hibernate, and also calls out
to a Flask REST API that hosts the AI/ML module built with scikit-learn.
That AI module covers the restock prediction engine, sales trend analysis,
and the fast/slow recommendation engine.

If the Python AI service is not running, the Java app automatically falls
back to an equivalent built-in rule-based AI engine, so AI insights always
work.
https://github.com/Anushika74/Smart-Inventory-Management-System/blob/main/systemArchitecture.png

TECH STACK

  Web / Backend:   Java 17, Spring Boot 3.3, Spring MVC, Spring Security
  Views:           Thymeleaf, Bootstrap 5, Chart.js
  Persistence:     Spring Data JPA, Hibernate, MySQL 8
  AI / ML:         Python 3, Flask, scikit-learn, pandas, numpy
  Build:           Maven


