
# Stockly
## Warehouse Stock Analysis & Storage Optimization

### Overview

Stockly is a personal software project designed to analyze warehouse stock data exported from SAP and support the optimization of storage locations.

The application processes pallet-level inventory information and identifies potential movements to improve space utilization, consolidate stock and reduce unnecessary handling activities.

The project was inspired by real operational challenges in warehouse management.

---

### The Problem

Warehouse stock can become distributed across multiple storage locations, creating unused capacity and making storage management less efficient.

Identifying suitable pallet movements manually can require time and repeated analysis of inventory data.

Stockly aims to turn exported stock information into practical and structured movement suggestions.

---

### Key Features

- **Stock data analysis:** processes inventory information exported from SAP, with individual pallet records.
- **Article and batch grouping:** evaluates stock according to article and batch number.
- **Storage optimization:** identifies potential opportunities to consolidate pallets in drive-in locations.
- **Movement suggestions:** generates proposed pallet movements based on defined operational rules.
- **Operational priorities:** considers storage conditions and stock priorities when evaluating possible movements.
- **Mobile workflow:** provides an operational list that can be consulted from a smartphone, including a guided operating mode.

---

### Optimization Logic

The application evaluates possible movements using warehouse-specific rules:

1. Analyze stock by article and batch.
2. Identify compatible pallets and storage locations.
3. Evaluate opportunities to consolidate occupied locations.
4. Consider operational priorities and storage constraints.
5. Preserve existing locations when a proposed movement does not provide a meaningful benefit.
6. Generate a structured list of suggested movements.

The objective is to support decision-making rather than blindly move stock.

---

### Expected Benefits

- Better utilization of available storage capacity.
- Reduced fragmentation of stored stock.
- More structured pallet movement planning.
- Less manual analysis of inventory data.
- Easier access to operational instructions from mobile devices.

---

### Technologies & Concepts

- SAP S/4HANA data exports
- Microsoft Excel
- Data analysis and processing
- Business rules and operational logic
- Warehouse process optimization
- Mobile-oriented application design
- AI-assisted development

---

### Project Approach

Stockly was developed around a practical business problem.

The work involved analyzing operational requirements, defining optimization rules, translating warehouse logic into application behavior and testing the resulting suggestions against real-world use cases.

**Stockly demonstrates how operational experience and software development can work together to improve business processes.**
