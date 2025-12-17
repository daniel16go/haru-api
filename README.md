# haru-api
HARU API: Backend core for a PWA expense tracker. Built with .NET 10 (Clean Arch) and PostgreSQL. It implements the "Golden Rule": dynamic financial periods are initiated *only* when a transaction is marked as 'IsPeriodAnchor=true', moving away from standard calendar months for precise, user-centric expense tracking.
