# Vendor Dashboard

This project is a Vendor Dashboard built using React. It allows vendors to manage their firms and products. The dashboard includes features for adding firms, adding products, viewing all products, and user authentication (login and registration).

## Features

- **User Authentication**: Vendors can register and log in to the system.
- **Firm Management**: Vendors can add and manage their firms.
- **Product Management**: Vendors can add, view, and delete products.
- **Responsive Design**: The dashboard is designed to be responsive and user-friendly.

## Project Structure

The project is structured as follows:

```
DASHBOARD
├── node_modules
├── public
├── src
│   ├── vendorDashboard
│   │   ├── components
│   │   │   ├── forms
│   │   │   │   ├── AddFirm.jsx
│   │   │   │   ├── AddProduct.jsx
│   │   │   │   ├── Login.jsx
│   │   │   │   ├── Register.jsx
│   │   │   │   ├── VendorLogin.jsx
│   │   │   │   └── VendorRegister.jsx
│   │   │   ├── AllProducts.jsx
│   │   │   ├── NavBar.jsx
│   │   │   ├── NotFound.jsx
│   │   │   ├── SideBar.jsx
│   │   │   └── Welcome.jsx
│   │   ├── helpers
│   │   │   └── ApiPath.js
│   │   ├── pages
│   │   │   └── LandingPage.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
└── index.html
```

## Key Components

- **AddFirm.jsx**: Component for adding a new firm.
- **AddProduct.jsx**: Component for adding a new product.
- **Login.jsx**: Component for vendor login.
- **Register.jsx**: Component for vendor registration.
- **Welcome.jsx**: Component displaying a welcome message.
- **AllProducts.jsx**: Component for displaying all products.
- **NavBar.jsx**: Navigation bar component.
- **NotFound.jsx**: Component for displaying a 404 error page.
- **SideBar.jsx**: Sidebar component for navigation.
- **LandingPage.jsx**: Main landing page component.
- **ApiPath.js**: Configuration file for API URL.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/vendor-dashboard.git
   ```
2. Navigate to the project directory:
   ```bash
   cd vendor-dashboard
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

- **Login/Register**: Use the login and register forms to authenticate.
- **Add Firm**: Navigate to the "Add Firm" section to add a new firm.
- **Add Product**: Navigate to the "Add Product" section to add a new product.
- **View Products**: Navigate to the "All Products" section to view and manage products.

## API Configuration

The API URL is configured in `ApiPath.js`. By default, it points to a hosted backend:

```javascript
export const API_URL = "https://backend-nodejs-suby.onrender.com";
```

## Styling

The project uses custom CSS for styling, with fonts imported from Google Fonts. The main styles are defined in `App.css`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- React
- React Router
- React Loader Spinner
- Google Fonts

---

This README provides an overview of the project structure, features, and instructions for installation and usage. Adjustments can be made based on specific project requirements or additional features.
