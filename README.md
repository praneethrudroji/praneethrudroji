# Praneeth Rudroji

Software engineer at **Inovalon**, based in Hyderabad, India. I build backend services in C# and .NET, and the React interfaces that sit in front of them.

[Website](https://praneethrudroji.github.io) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/praneethrudroji/) &nbsp;·&nbsp; [praneethrudroji@gmail.com](mailto:praneethrudroji@gmail.com)

---

## What I work on

My day-to-day sits between service design and delivery: decomposing systems into services with clear ownership and contracts, keeping data consistent across those boundaries, and making the result observable and safe to deploy. The repositories here are a deliberate sandbox for that practice rather than production work, so they favour clarity over completeness.

## Selected work

**ParkPlace** — a commerce system split by business domain rather than by technical layer, with each service owning its data and exposing a versioned HTTP contract.

| Repository | Responsibility |
| --- | --- |
| [parkplace-ui](https://github.com/praneethrudroji/parkplace-ui) | React 19 and Vite storefront: catalogue browsing, cart, checkout, order history and a guarded admin area |
| [ProductService](https://github.com/praneethrudroji/ProductService) | Product catalogue and pricing |
| [CartService](https://github.com/praneethrudroji/CartService) | Cart lifecycle and line-item rules |
| [OrderService](https://github.com/praneethrudroji/OrderService) | Order placement and order history |
| [InventoryService](https://github.com/praneethrudroji/InventoryService) | Stock levels and reservations |

Also here: [CodeAndDesignPatterns](https://github.com/praneethrudroji/CodeAndDesignPatterns), worked examples of design patterns and refactorings in C#, and [praneethrudroji.github.io](https://github.com/praneethrudroji/praneethrudroji.github.io), the source of my personal site.

## Technical background

| Area | Detail |
| --- | --- |
| Languages | C#, JavaScript, SQL |
| Backend | .NET, ASP.NET Core, REST APIs, service decomposition |
| Front end | React, React Router, Tailwind CSS, Vite |
| Data | SQL Server |
| Platform and delivery | Azure, Docker, Kubernetes, GitHub Actions |

## How I approach engineering

I prefer boring, legible solutions and short feedback loops. Before adding a service or an abstraction I want to name the problem it solves and the cost of carrying it. I document the decisions that were genuinely contested and leave the obvious ones to the code. Reviews are for reasoning, not for style preferences a linter can settle.

## Contact

The quickest route is [email](mailto:praneethrudroji@gmail.com) or [LinkedIn](https://www.linkedin.com/in/praneethrudroji/). I am glad to talk about .NET service architecture, front-end and back-end contracts, or reviewing a design you are unsure about.
