# 🛒 EcommerceWeb - A Modern E-Commerce Platform

**EcommerceWeb** is a modern, feature-rich e-commerce platform designed specifically for book lovers. Built with **ASP.NET Core MVC** and **Entity Framework Core**, this project showcases the key features of a modern online store. The project follows **Layered Architecture**, ensuring clear separation of concerns between different parts of the application, making it easy to maintain and scale.

# 🌐 Live Demo

<div align="center">

🔗 **Experience the platform live:** [debugger-squad-production.up.railway.app](https://debugger-squad-production.up.railway.app/)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit-blue?style=for-the-badge)](https://debugger-squad-production.up.railway.app/)

</div>

## 🤝 Team Information: Debugger Squad

<div align="center">

| 👤 Name     | Naimur Rahman                                | Monir Hossain                                       | Nasif Uz Zaman                                 |
| ----------- | -------------------------------------------- | --------------------------------------------------- | ---------------------------------------------- |
| 🎯 Role     | Mentor                                       | Member                                              | Member                                         | 
| 💻 GitHub   | [Naimurrahman76](https://github.com/Naimurrahman76)      | [monir-devx](https://github.com/monir-devx) | [NasifUzZaman38](https://github.com/NasifUzZaman38)    |
| 🔗 LinkedIn | [LinkedIn](https://www.linkedin.com/in/naimur76/) | [LinkedIn](https://www.linkedin.com/in/monir-hossain-mbstu/)  | [LinkedIn](https://www.linkedin.com/in/nasif-uz-zaman-30139330a/) |

</div>


## 📁 Repository Structure

```
Ecommerce/
├── Ecommerce.DataAccess/
│   ├── Data/
│   ├── DbInitializer/
│   ├── Migrations/
│   ├── Repository/
│
├── Ecommerce.Models/
│   ├── Models/
│   └── ViewModels/
│
├── Ecommerce.Utility/
│   └── Utilities/
│       ├── EmailSender/
│       ├── StripeSettings/
│       └── SD.cs
│
├── EcommerceWeb/
│   ├── Areas/
│   │   ├── Admin/
│   │   │   ├── Controllers/
│   │   │   └── Views/
│   │   ├── Customer/
│   │   │   ├── Controllers/
│   │   │   └── Views/
│   │   └── Identity/
│   │       └── Pages/
│   ├── ViewComponents/
│   ├── Views/
│   ├── wwwroot/
│   └── Properties/
│
├── Ecommerce.Tests/
│   ├── ControllerTests/
│   └── RepositoryTests/
│
└── Ecommerce.sln
```

---
## 📝 Tools and Technologies

<table align="center">
  <tr>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Microsoft_.NET_logo.png" alt="ASP.NET Core" height="60" />
      <p><b>ASP.NET Core MVC</b></p>
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Csharp_Logo.png" alt="C#" height="60" />
      <p><b>C#</b></p>
    </td>
    <td align="center">
      <img src="https://cdn.worldvectorlogo.com/logos/javascript-1.svg" alt="JavaScript" height="60" />
      <p><b>JavaScript</b></p>
    </td>
    <td align="center">
      <img src="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png" alt="Bootstrap" height="60" />
      <p><b>Bootstrap</b></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><b>Entity Framework Core</b></p>
    </td>
    <td align="center">
      <img src="https://schwabencode.com/contents/logos/mssql-server.png" alt="SQL Server" height="60" />
      <p><b>SQL Server</b></p>
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" alt="PostgreSQL" height="60" />
      <p><b>PostgreSQL</b></p>
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/SQLite370.svg" alt="SQLite" height="60" />
      <p><b>SQLite</b></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <p><b>ASP.NET Identity</b></p>
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Login" height="60" />
      <p><b>Facebook Login</b></p>
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/ba/Stripe_Logo%2C_revised_2016.svg" alt="Stripe" height="60" />
      <p><b>Stripe Payment</b></p>
    </td>
    <td align="center">
      <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" height="60" />
      <p><b>Git & GitHub</b></p>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" alt="Docker" height="60" />
      <p><b>Docker</b></p>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/22525303?s=200&v=4" alt="Fly.io" height="60" />
      <p><b>Fly.io</b></p>
    </td>
    <td align="center">
      <img src="https://railway.app/brand/logo-light.png" alt="Railway" height="60" />
      <p><b>Railway</b></p>
    </td>
    <td align="center">
      <p><b>xUnit</b></p>
    </td>
  </tr>
</table>


## 📝 Project Description

**EcommerceWeb** is a modern, full-featured e-commerce platform for book lovers, built with **ASP.NET Core MVC** and **Entity Framework Core**, adhering to **Clean Architecture principles**. It is designed to serve both as a robust real-world application and a valuable learning resource for developers. The platform supports multi-role access, secure payment processing, product management, and a seamless user experience through a responsive and interactive UI.

## 🚀 Key Features

### 🛒 Product & Category Management
- Admins and employees can **create, update, and delete** products and categories.
- Products include **pricing, discounts, inventory tracking**, and **image uploads** via a dynamic UI.

### 👥 Role-Based Access Control
- Four distinct roles: **Admin**, **Employee**, **Customer**, and **Company**.
- Each role has tailored **permissions** and **dashboard views**.

### 🛍️ Shopping Cart & Secure Checkout
- Persistent shopping cart experience for both **guest** and **logged-in** users.
- **Stripe-powered payment integration** with test and live environments.

### 🔒 Authentication & Authorization
- **ASP.NET Identity**-based authentication with **role management**.
- Supports external login with **Facebook authentication**.
- Custom workflows for **Company** users (e.g., Net 30 billing).

### 📦 Order Management
- Customers can **track order status** and **view history**.
- Admins can **manage orders**, including **refunds via Stripe** and **shipping updates**.

### 🛠️ Admin Dashboard
Feature-rich interface to manage:
- Products with images
- Categories
- Companies and their users
- Orders and statuses
- User roles and access

### 💡 Enhanced UI/UX
- **DataTables**: Sorting, searching, and pagination in admin tables.
- **Toastr**: Real-time notification feedback.
- **TinyMCE**: Rich text editor for product descriptions.
- **SweetAlert**: Clean and modern modal dialogs.
- **Carousel**: Multi-image support in product gallery.

### ⚙️ Architecture & Backend
- Follows **Repository** and **Unit of Work** patterns.
- Includes **DBInitializer** to seed roles and admin accounts on first run.
- Structured into multiple projects: `Models`, `DataAccess`, `Utility`, and `Web`.

### 🧪 Testing & CI/CD
- **xUnit** test coverage for controllers and repositories.
- **Dependency Injection & Mocking** for testability.
- **GitHub Actions + SonarCloud** for CI and code quality checks.

### 🗃️ Database & Deployment
- **SQL Server** with **Entity Framework Migrations**.
- Deployment-ready on **Railway**, **Fly.io**, and **SQLite** for local development.

---

## 📸 Project Screenshots

<table>
  <tr>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/7wadeve2vnl_1746467286600.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/hdrfhvcrho7_1746467648367.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/v4qrho8n7ac_1746467747207.png" width="300"/></td>
  </tr>
  <tr>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/rsafa4rwfl_1746467782535.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/p40opw38te_1746467859958.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/rc8lttex9y_1746467902630.png" width="300"/></td>
  </tr>
  <tr>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/6cpribuxve9_1746467928294.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/8hutxq6wwr9_1746467962030.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/cpfv323jsze_1746467999381.png" width="300"/></td>
  </tr>
  <tr>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/1rhoczro9qs_1746470459555.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/xyechtdrkqe_1746470667923.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/e5bmvtylxwb_1746470756466.png" width="300"/></td>
  </tr>
  <tr>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/dt30k8p1b4a_1746470887810.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/bmib40u37yl_1746471087329.png" width="300"/></td>
    <td><img src="https://actvkmglkippzhzwzuzo.supabase.co/storage/v1/object/public/product_screenshots/31z0zutaq6a_1746471316416.png" width="300"/></td>
  </tr>
</table>


## 📦 Resources

- [Project Documentation](docs/)
- [Development Setup Guide](docs/setup.md)
- [Contributing Guidelines](CONTRIBUTING.md)

For detailed information, please visit our [**Wiki page**](https://github.com/monir-devx/debugger-squad/wiki).
