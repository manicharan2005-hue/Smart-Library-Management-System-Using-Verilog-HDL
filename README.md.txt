# Smart Library Management System (Verilog HDL)

## Project Description
This project simulates a simple library management system using Verilog HDL. It supports book issue, return, and availability tracking using an 8-bit register system.

## Features
- 8 books system
- Issue and return functionality
- User validation
- Book validation
- Availability tracking

## How it works
- Each bit represents a book
- 1 = available
- 0 = issued

## Files
- library_management.v → Main design
- library_management_tb.v → Testbench
- README.md → Documentation

## How to Run
Use EDA Playground:
1. Paste design code
2. Paste testbench
3. Run simulation

## Output
Shows:
- Issue success/failure
- Return success/failure
- Valid/invalid user/book
- Book availability status