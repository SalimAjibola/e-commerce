# e-commerce

This repository contains a responsive and user-friendly e-commerce web application built using React, Next.js, and Tailwind CSS. The app fetches and displays product data from the Fake Store API, providing users with a seamless online shopping experience.

## Live Demo

[View Live Project](https://e-commerce-theta-self-47.vercel.app/) (Deploy on Vercel.)

---

## Features

### 1. **Responsive Design**
- Fully responsive layout that adapts to mobile, tablet, and desktop screens.
- Built with modern UI principles using Tailwind CSS.

### 2. **Product Listings**
- Dynamic fetching of product data from the [Fake Store API](https://fakestoreapi.com/).
- Displays product categories, names, prices, and descriptions.

### 3. **Search and Filter**
- Search functionality to find specific products.
- Filter products by category.

### 4. **Product Details Page**
- Detailed view of individual products, including images, descriptions, and prices.

### 5. **WCAG Accessibility Compliance**
- Keyboard navigability for interactive elements.
- Semantic HTML structure and ARIA attributes for accessibility.

### 6. **Performance Optimizations**
- Lazy-loaded images and components for faster performance.
- Optimized API calls using Next.js `getStaticProps` and `getServerSideProps`.

### 7. **Theming**
- Implemented light and dark mode toggle using Tailwind's dark mode utilities.

---

## Technologies Used

### Frontend:
- **React.js**: For building dynamic user interfaces.
- **Next.js**: For server-side rendering and SEO-friendly structure.
- **Tailwind CSS**: For fast and flexible styling.
- **TypeScript** (if used): For type safety and maintainability.

### API:
- **Fake Store API**: Provides product data for the application.

### Hosting:
- **Vercel** (Recommended): For deployment.

---

## Installation

### Prerequisites
- Node.js (v16 or above recommended)
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/SalimAjibola/e-commerce.git
   ```
2. Navigate to the project directory:
   ```bash
   cd e-commerce
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## API Integration
This project integrates the [Fake Store API](https://fakestoreapi.com/) to fetch product data. The API endpoints used include:
- **All Products**: `https://fakestoreapi.com/products`
- **Single Product**: `https://fakestoreapi.com/products/{id}`
- **Categories**: `https://fakestoreapi.com/products/categories`

---

## Folder Structure

```
.
├── components
│   ├── Header.js     # Navigation bar and site header
│   ├── ProductCard.js # Individual product card component
│   ├── Footer.js     # Footer section
├── pages
│   ├── index.js      # Homepage
│   ├── product/[id].js # Dynamic product details page
├── public
│   ├── images        # Static assets
├── styles
│   ├── globals.css   # Global styles
├── README.md         # Project documentation
```

---

## Challenges Faced
1. **API Integration:**
   - Handling inconsistent data from the API.
   - Solution: Implemented error handling for API calls using `try-catch` blocks.

2. **Responsiveness:**
   - Ensuring consistent design across multiple devices.
   - Solution: Utilized Tailwind's utility classes for responsive design.

3. **Performance Optimization:**
   - Reducing load time for large datasets.
   - Solution: Implemented lazy-loading for images and components.

---

## Future Enhancements
1. **Shopping Cart:**
   - Add functionality to allow users to add products to a cart and manage their purchases.

2. **Authentication:**
   - Implement user authentication for login/logout functionality.

3. **Pagination:**
   - Add pagination for product listings to handle larger datasets efficiently.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## License

This project is open source and available under the MIT License.

---

## Contact

For any inquiries or feedback, please reach out:
- **Email:** salimajibola06@gmail.com
- **GitHub:** [SalimAjibola](https://github.com/SalimAjibola)
