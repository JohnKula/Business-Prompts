Engineered Specification: Enterprise Spreadsheet Formula Architecture

Task: Engineer a resilient, scalable spreadsheet formula solution and explain its computational logic, edge-case limitations, and data validation prerequisites.

Environment & Specifications:
• Platform: [Microsoft Excel 365 / Google Sheets / Excel 2019 Legacy]
• Table Name / Range: [e.g., SalesData!A2:G5000]
• Key Columns Involved:
    • Column A: [Order Date, Format: YYYY-MM-DD]
    • Column C: [Region, String]
    • Column F: [Revenue, Currency]
    • Column G: [Status, Discrete Values: "Closed", "Pending", "Cancelled"]

Target Computational Goal:
[Describe requirement precisely, e.g., Calculate rolling 90-day average revenue for "Closed" orders strictly in the "EMEA" region, ignoring blank rows and non-numeric entries.]

Engineering Constraints:
1. Provide modern dynamic array formulas (e.g., LET, LAMBDA, FILTER, XLOOKUP) if Excel 365 is specified; fallback to nested INDEX/MATCH for legacy environments.
2. Enforce error-handling wrappers (e.g., IFERROR, ISBLANK) to prevent #SPILL!, #CALC!, or #N/A runtime failures.
3. Optimize for computational performance over large datasets, avoiding volatile functions like OFFSET or INDIRECT unless strictly necessary.

Output Architecture:
1. Primary Production Formula: Code block containing the exact syntax ready to copy-paste.
2. Computational Logic Breakdown: Step-by-step breakdown of how each nested argument functions.
3. Performance & Edge Case Audit: Identification of how formula behaves when matches are zero, dates are invalid, or ranges expand.
