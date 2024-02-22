<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
  <p>
    An interactive, modern, and powerful datatable library for handling large amounts of tabular data in web applications.
    <br>
    <a href="https://empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/datatable/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/datatable/issues/new">Request Feature</a>
  </p>
</div>

## 📖 About The Project

datatable is a powerful library designed to render and manage large amounts of tabular data in web applications. With features like inline editing, keyboard navigation, column reordering, and more, it offers a robust yet user-friendly solution for handling data tables. Originally built for Empress, it's now available for integration into your projects.

## 🌟 Key Features

- **Custom Formatters:** Define your own custom data formats for cells.
- **Inline Editing:** Edit data directly within the table.
- **Keyboard Navigation:** Navigate through the table using your keyboard.
- **Column Reordering:** Easily rearrange columns according to your preference.
- **Large Number of Rows:** Handle vast amounts of data with ease.

## 🛠 Technical Stack and Setup Instructions

datatable is built with:

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)

To integrate datatable into your project:

### Prerequisites

Ensure Node.js is installed on your machine. You'll also need `sortablejs`.

### Installation

Clone the repository:

```sh
git clone https://github.com/empress-eco/datatable.git
```

Install the library via npm or yarn:

```sh
npm install Empress-datatable
```

Or via yarn:

```sh
yarn add Empress-datatable
```

## ✨ Usage

Here's a quick start guide:

```js
const datatable = new DataTable('#datatable', {
  columns: [ 'First Name', 'Last Name', 'Position' ],
  data: [
    [ 'Don', 'Joe', 'Designer' ],
    [ 'Mary', 'Jane', 'Software Developer' ]
  ]
});
```

## 🤝 Contribution Guidelines

We welcome your contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the MIT License.

Special thanks to the [Empress Community](https://Empress.io/) for their foundational contributions to this library. Their innovation and dedication have been instrumental in building the functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.