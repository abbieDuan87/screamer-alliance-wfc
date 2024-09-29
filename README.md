# Screamer Alliance WFC Website

This is the official website for Screamer Alliance Women's Football Club, built using [Hugo](https://gohugo.io/) and the [Blowfish](https://blowfish.page/) theme. The site is live at [https://abbieduan87.github.io/screamer-alliance-wfc/](https://abbieduan87.github.io/screamer-alliance-wfc/) and styled with [Tailwind CSS](https://tailwindcss.com/).

## Project Structure

- **Hugo:** A fast and flexible static site generator.
- **Blowfish Theme:** A clean and minimalist theme for Hugo.
- **Tailwind CSS:** A utility-first CSS framework for customizing styles.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

Make sure you have the following installed:

- [Hugo](https://gohugo.io/getting-started/installing/) (version 0.85.0 or later)
- [Node.js](https://nodejs.org/) (for Tailwind CSS)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/screamer-alliance-wfc.git
   cd screamer-alliance-wfc
   ```

2. Install dependencies:

   If you're using Tailwind CSS, you'll need to install the necessary npm packages:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   hugo server
   ```

   The site will be available at `http://localhost:1313/`.

## Deployment

This site is automatically deployed to [GitHub Pages](https://pages.github.com/) at [https://abbieduan87.github.io/screamer-alliance-wfc/](https://abbieduan87.github.io/screamer-alliance-wfc/) whenever changes are pushed to the `main` branch. Make sure to check the `public/` folder for the generated site files after running `hugo`.

## Customization

- **Content:** All posts and pages are in the `content/` directory.
- **CSS:** Tailwind CSS configuration can be found in `tailwind.config.js`. Custom CSS can be added in the `assets/css/` directory.
- **Configuration:** Modify the `config.toml` file to update site settings like title, menu, and social links.

## Contributing

Feel free to fork the repository and submit a pull request if you'd like to contribute.
