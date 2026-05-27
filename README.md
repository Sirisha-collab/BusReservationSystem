Bus Reservation System (ASP.NET Core MVC - Code First)

**Tech Stack**
ASP.NET Core MVC (.NET 6/7)
Entity Framework Core (Code First)
SQL Server
ASP.NET Core Identity (Authentication)
Bootstrap (UI Styling)
LINQ

**Architecture**
MVC Pattern (Model–View–Controller)
Code First Approach using EF Core
Repository-style separation (if implemented)
Authentication via Identity framework

**⚙️ Setup Instructions**

1. Clone Repository
git clone https://github.com/your-username/BusReservationSystem.git
2. Open Solution
3. Configure Database
Update appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=BusReservationDB;Trusted_Connection=True;"
}
4. Run Migrations
Open Package Manager Console:

Add-Migration InitialCreate
Update-Database
5. Run Project: Ctrl + F5

**📊 Future Improvements**

Real payment gateway integration (Stripe/Razorpay)
QR-based ticket generation
Email/SMS ticket confirmation
Real-time seat locking system
Microservices-based architecture
