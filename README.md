**ToyGallaryAPI - ASP.NET Core MVC Project**
A web application that integrates with the Advertising API to fetch and display trending toys, automate updates, and optimize affiliate marketing strategies. Built with ASP.NET Core MVC 8, Entity Framework, and RESTful APIs.

**Project Overview**
This project automates fetching toy data from Toy API, displays it in dynamic categories (e.g., "Best STEM Toys"), and optimizes affiliate marketing through SEO, retargeting, and analytics. Key components include:

**Automation**: Daily updates via background services.

**SEO Optimization**: Focus on long-tail keywords and product reviews.

**Features**
API Integration & Automation

Fetch high-converting toys daily.

Filter by ratings, reviews, and categories.

User Engagement

Comparison tables and "Best for" sections.

"Deals of the Day" with affiliate links.

SEO & Social

SEO-optimized product reviews.

Shareable toy lists for Pinterest and social media.


**Analytics**

Track clicks and sales via Amazon reports.

A/B testing and heatmaps.

**Prerequisites**
.NET 8 SDK

Visual Studio 2022 (or JetBrains Rider)

SQL Server

Amazon Affiliate Account (for API credentials)

Facebook/Google Ads account (for retargeting).

**Installation**
Clone the repository:

bash
Copy
git clone [https://github.com/yourusername/AmazonAffiliateToys.git](https://github.com/Ruchilavichare/ToyGallaryAPI)
cd AmazonAffiliateToys
Restore NuGet packages:

bash
Copy
**dotnet restore**
Set up the database:

Update appsettings.json with your SQL Server connection string.

**Run EF Core migrations:**

bash
Copy
dotnet ef database update

Retargeting Ads
Add Facebook/Google Ads tracking scripts to Views/Shared/_Layout.cshtml.

**Usage**
Run the Application

bash
Copy
dotnet run
Visit https://localhost:7272 in your browser.

**View Trending Toys**

Navigate to /Toys to see product listings.

Use dropdowns to filter by category (e.g., "Ages 3-5").

Automated Features

Daily toy updates run automatically in the background.

Deals of the Day are refreshed every 24 hours.
