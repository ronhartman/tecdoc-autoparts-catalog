# Vehicle Parts Catalog - A decent TecDoc Alternative (not as complete as Tecdoc but could work for small & medium projects)

This project, built on **Symfony 7.1**, provides a foundation to help you integrate with our **[Vehicle Parts Catalog API](https://auto-parts-catalog.apiprofile.com/)**. The API enables precise automotive parts identification, cross-referencing, and vehicle application data. Start building your app today using the available API functionalities.

**API Documentation**: [Auto Parts Catalog](https://auto-parts-catalog.apiprofile.com/)

## Key Features
- **Part Identification**: Search parts by vehicle make, model, and year.
- **Cross-Referencing**: Find interchangeable parts across manufacturers.
- **Vehicle Application Data**: Detailed part compatibility for various vehicles.
- **Catalog Management**: Easily update and publish new parts, specifications, and pricing.
- **Streamlined Ordering**: Simplify procurement by integrating our API.
- **Technical Data**: Comprehensive specs, including dimensions and weights.
- **Seamless Integration**: Connect with inventory management or e-commerce platforms.

## Getting Started

Follow these steps to run the project locally:

### Step 1: Clone the repository
```bash
git clone https://github.com/catamc90/auto-parts-catalog

### Step 2: Install dependencies
```bash
composer install
```

### Step 3: Add API Key
Update the `.env` file with your [API key](https://auto-parts-catalog.apiprofile.com/):
```
API_KEY=your_api_key_here
```

### Step 4: Start the Symfony server
```bash
symfony server:start
```

### Step 5: You're all set!
Your project is up and running. Start exploring the API to build your own app.

## Available API Methods

The API methods are available in the `CatalogApi.php` class. Controllers handle the data flow in the application:

1. **HomeController** - Main landing point.
2. **ManufacturersController** - Retrieve manufacturers.
3. **ModelsController** - Fetch vehicle models.
4. **TypesController** - Access vehicle types.
5. **CategoryController** - List categories.
6. **ArticlesController** - Retrieve parts and articles.

## Demo

Check out the live demo here: [Auto Parts Catalog Demo](https://auto-parts-catalog.apiprofile.com/)

