# OrgPay

**Stellar-Powered Payroll & USDC Settlement**

OrgPay is a payroll management platform built on the Stellar network that enables organizations to manage employees, create payroll runs, and execute multiple USDC payments on Stellar Testnet.

The MVP focuses on simplifying the process of preparing, executing, and tracking organization-wide digital-asset payroll payments.

> **Network:** Stellar Testnet  
> **Status:** MVP  
> **Asset:** USDC  
> **Use Case:** Payroll & Organizational Payments

---

## Overview

Managing payroll for employees or contractors can become difficult when payments need to be sent individually and transaction confirmations have to be tracked manually.

OrgPay provides a single workflow for managing employee payment information, creating payroll runs, executing multiple Stellar payments, and tracking the resulting transactions.

### Core Flow

**Add Employees → Set Salaries → Create Payroll Run → Review Payroll → Execute Payments → Track Transactions**

---

## Problem

Organizations paying employees or contractors in digital assets often need to:

- Manage multiple employee wallet addresses
- Maintain individual payment amounts
- Calculate total payroll
- Process multiple payments
- Track individual payment statuses
- Verify blockchain transactions

Without a dedicated workflow, these tasks can require multiple tools and significant manual coordination.

---

## Solution

OrgPay provides an organization-focused payroll workflow that combines payroll management with Stellar payment settlement.

An administrator can:

1. Add employees
2. Add their Stellar wallet addresses
3. Assign USDC salary amounts
4. Create a payroll run
5. Review the total payroll amount
6. Execute payments on Stellar Testnet
7. Track individual payment status
8. View the corresponding transaction hashes

---

## Features

### Employee Management

Organizations can manage employee payment information including:

- Employee name
- Stellar wallet address
- USDC salary amount

### Payroll Runs

Create a payroll run containing multiple employees and calculate the total amount required before execution.

### Stellar USDC Settlement

Execute USDC payments to employee Stellar wallets through Stellar Testnet.

### Payment Tracking

Track each employee's payment status:

```text
Pending
   ↓
Processing
   ↓
Paid
