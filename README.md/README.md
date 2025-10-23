# Automated Collection System – Python + Power BI + SAP

This project demonstrates a reactive collection automation solution, integrating data extracted from SAP, processed with Python, and visualized through Power BI.

## Purpose

Automate the collection process with a focus on:
- Identifying delinquent customers
- Automatically sending personalized emails
- Visualizing metrics in Power BI
- Graphical interface for executing actions

## Project Structure

### SCRIPTS/
- `interface.py`: graphical interface built with PySide6
- `reativa.cobranca.py`: script for automated reactive collection based on the Aging table

### INPUT/
- `AGING.png`: visual reference of the Aging dataset

### INTERFACE/
- `INTERFACE.png`: screenshot of the system interface

### DOCS/
- `DASHBOARD.png`: executive view of the Power BI report
- `Guia para instalar Python.pdf`: installation and usage instructions

## Technologies Used

- Python 3.10.11  
- Pandas  
- PySide6  
- smtplib + Outlook  
- Power BI (Power Query and DAX)  
- SAP (via GUI Scripting)

## Notes

- Scripts use fictitious data for demonstration purposes  
- Python version 3.10.11 is required for compatibility  
- Outlook must be pre-configured for email sending

---

© Project developed by Bruno Ricardo as a technical demonstration of process automation in the Order to Cash cycle.