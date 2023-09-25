# Login_Handler

Welcome to the **Login_Handler** repository! This is a React-based web application designed to simplify the user login process by ensuring that a user is not prompted to log in repeatedly. Once a user logs in, they will remain logged in until they decide to log out.

## Features

- **Persistent User Login**: After the initial login, users will not be prompted to sign in again until they manually log out.
- **React Hooks**: Utilizes the `useEffect()` and `useState()` hooks for optimal component lifecycle and state management.
- **Fragments & Portals**: Integrated use of React fragments and portals for more flexible and efficient DOM rendering.
- **Direct DOM Manipulation**: Utilizes the `useRef()` hook in combination with `react-dom` for specific rendering tasks.
- **CSS Modules**: Styles are encapsulated using CSS modules, ensuring that styling is specific to components and avoids global conflicts.

## Prerequisites

- Node.js
- npm or yarn

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/rimshaRasheed/Login_Handler.git
   ```
2. Change to the project directory:
   ```
   cd Login_Handler
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Run the application:
   ```
   npm start
   ```

The application will open in your default browser at `http://localhost:3000`.

## Usage

1. **Sign Up**: If you're a new user, sign up with your desired credentials.
2. **Login**: Use your credentials to log in. Upon successful login, the application will remember your session.
3. **Logout**: If you wish to end your session, you can manually log out. Upon doing so, you'll be required to log in again the next time.

## Contributions

Contributions are welcome! Please read the [contributing guidelines](link-to-your-contributing-guideline) before getting started.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

