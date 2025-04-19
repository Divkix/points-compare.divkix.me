# Credit Card Partner Comparison

This project is a web-based tool for comparing credit card transfer partners across multiple programs. It uses a Venn diagram to visualize overlapping and unique partners between selected programs, helping users make informed decisions about point transfers.

## Features

- **Dynamic Venn Diagram**: Visualize overlapping and unique transfer partners between selected programs.
- **Partner Details**: View detailed lists of airline and hotel partners for each segment of the Venn diagram.
- **Award Booking Links**: Quick access to award booking tools like [point.me](https://point.me), [seats.aero](https://seats.aero), and [rooms.aero](https://rooms.aero).
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **React**: For building the user interface.
- **D3.js**: For rendering the Venn diagram.
- **Venn.js**: For generating Venn diagram data.
- **Tailwind CSS**: For styling the application.
- **Babel**: For JSX and modern JavaScript transpilation.

## Getting Started

### Prerequisites

To run this project, you need a modern web browser with JavaScript enabled. No additional setup is required as the project uses CDN-hosted libraries.

### Running the Project

1. Clone this repository or download the `index.html` file.
2. Open the `index.html` file in your web browser.

### Usage

1. Select the number of programs to compare using the dropdown menu.
2. Choose programs from the available options (e.g., Amex, Chase, Citi, etc.).
3. View the Venn diagram and partner details below.
4. Use the award booking links for further research.

## Data Sources

The transfer partner data is hardcoded in the application and includes the following programs:

- **Amex**
- **Bilt**
- **Chase**
- **Capital One**
- **Citi**

Each program includes a list of airline and hotel partners.

## Notes

- Partners marked with `(via Hawaiian)*` indicate indirect transfers via Hawaiian Airlines. These transfers may change following the Alaska/Hawaiian merger integration (potentially late 2025 or beyond). Always verify transfer ratios and availability before transferring points.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

- [D3.js](https://d3js.org) for data visualization.
- [Venn.js](https://github.com/benfred/venn.js) for Venn diagram generation.
- [Tailwind CSS](https://tailwindcss.com) for styling.
- [React](https://reactjs.org) for building the UI.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## Contact

For questions or feedback, please open an issue in the repository.