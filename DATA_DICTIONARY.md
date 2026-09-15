# Data Dictionary

## DATA_RAW
| Field | Meaning |
|---|---|
| Date | Order date |
| Order ID | Unique order identifier |
| Customer ID | Customer identifier |
| Customer Name | Customer name |
| Product ID | Product identifier |
| Product | Product name |
| Category | Product category |
| Quantity | Units sold |
| Unit Price | Selling price per unit |
| Unit Cost | Cost per unit |
| Sales Channel | Sales source/channel |
| Payment Method | Payment method |
| Region | Geographic region |

## DATA_CLEAN
The clean layer retains the source fields and adds:
| Field | Meaning |
|---|---|
| Revenue | Quantity × Unit Price |
| Total Cost | Quantity × Unit Cost |
| Profit | Revenue − Total Cost |
| Profit Margin | Profit ÷ Revenue |
| Data Quality | Quality flag used by the workbook |

## CALCS
Monthly supporting values for:
- Revenue
- Profit
- Orders
