# Data Fetching and Search Application

A simple React application that fetches user data from an API and allows users to search through the fetched data based on the user's name.

## Features
- Fetches user data from [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users)
- Displays user details (name and email)
- Search functionality to filter users dynamically
- Displays loading state while fetching data
- Handles errors gracefully

## Technologies Used
- React
- CSS
- Fetch API

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/rambedade/braincell
   ```
2. Navigate to the project directory:
   ```sh
   cd repository-name
   ```
3. Install dependencies:
   ```sh
     npm create vite@latest ---template react
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

## Usage
- The application will automatically fetch user data when loaded.
- Use the search bar to filter users by name dynamically.
- If no users match the search, a "No users found" message will be displayed.
- If an error occurs while fetching data, an error message will be shown.

## Project Structure
```
project-folder/
│── src/
│   ├── components/
│   │   ├── Data.js  # Main component fetching and displaying users
│   │   ├── Data.css # Styling for the application
│   ├── styles/
│   │   
│   ├── App.js  # Root component
│── public/
│── package.json
│── README.md
```

## Deployment
To deploy the application, you can use platforms like:
- **Vercel** ([https://vercel.com](https://brain-c.vercel.app/))


## Contributing
Contributions are welcome! If you find any bugs or have feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, feel free to reach out!

- GitHub: (https://github.com/rambedade)
- Email: rambedade2308@gmail.com

