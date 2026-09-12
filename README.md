# Inventory Stock Analysis – Excel

## Project Overview

This project is a simple Excel-based inventory analysis created to understand basic inventory monitoring and replenishment decisions.

The project analyzes current stock levels against reorder levels and categorizes products as **Reorder, Optimal, or Overstock**.

## Project Preview

![Inventory Stock Analysis](./inventory-analysis.png)

## Objectives

* Monitor inventory levels
* Identify products that require replenishment
* Identify overstocked products
* Understand basic inventory management concepts
* Practice Excel formulas and conditional formatting

## Tools Used

* Microsoft Excel
* IF Functions
* COUNTIF
* Conditional Formatting
* Basic Data Analysis

## Stock Classification

| Status    | Meaning                                        |
| --------- | ---------------------------------------------- |
| Reorder   | Current stock is below the reorder level       |
| Optimal   | Stock is within the required range             |
| Overstock | Stock is significantly above the reorder level |

## Key Formula

The Stock Status was calculated using an IF formula:

`=IF(B2<D2,"Reorder",IF(B2>D2*2,"Overstock","Optimal"))`

preview.png

## Learning Outcome

This project helped me understand the basics of inventory monitoring, replenishment decisions and how Excel can be used to support supply chain operations.
