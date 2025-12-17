#HARU API (Backend)

The core backend service for HARU, a Progressive Web Application (PWA) designed for dynamic personal finance and expense tracking.

This API implements the crucial "Golden Rule" logic: a new financial period is triggered and started only when a transaction with the 'IsPeriodAnchor' flag set to true is registered. This system uses these anchors to define dynamic financial cycles, moving away from traditional calendar months.

Built with:
* .NET 10 (C#)
* Clean Architecture / Modular Monolith Pattern
* PostgreSQL Database
