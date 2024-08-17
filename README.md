
# Netflix GPT

A React-based Netflix clone that uses GPT for enhanced movie recommendations. This app is built with a focus on sleek UI using TailwindCSS, seamless user authentication with Firebase, and advanced integration with the TMDB API for fetching movie data. The project also includes multi-language support and a robust Redux setup for state management.

## Features

### Authentication
- **Login/Sign Up**: Secure login and registration forms with form validation.
- **Redirect Logic**: Automatically redirect users based on authentication status (e.g., redirect to the Browse page after login).
- **Profile Management**: Update user profiles, including display name and profile picture.
- **Sign Out**: Clear user sessions and redirect to the login page.
- **Bug Fixes**: Addressed issues with updating user display names and conditional page redirects.

### Browse (Post-Authentication)
- **Header**: Dynamic navigation bar with essential links.
- **Main Movie Display**: 
    - Background trailer autoplay (muted).
    - Display of title, description, and related movie suggestions.
- **Movie Lists**: 
    - Multiple categorized movie lists.
    - Fully responsive UI powered by TailwindCSS.

### Netflix GPT
- **GPT Search Bar**: Intelligent search powered by OpenAI, integrated with TMDB.
- **Movie Suggestions**: GPT-based movie suggestions displayed in a reusable movie list component.

## Project Structure and Implementation

1. **Create React App**: Bootstrapped the project using `create-react-app`.
2. **TailwindCSS**: Configured and customized styles using TailwindCSS.
3. **Routing**: Implemented React Router for page navigation.
4. **Forms & Validation**: Built and validated login and sign-up forms using React hooks like `useRef`.
5. **Firebase Setup**: Integrated Firebase for authentication, profile management, and deployment.
6. **Redux Store**: Configured Redux with slices for user and movie data.
7. **TMDB API**: Registered and integrated TMDB API to fetch movie data and trailers.
8. **OpenAI Integration**: Implemented OpenAI API for GPT-based search functionality.
9. **Custom Hooks**: Created hooks for fetching popular movies, now-playing movies, and more.
10. **Responsive Design**: Ensured a fully responsive design using TailwindCSS classes.
11. **Environment Variables**: Managed API keys using `.env` files (ensured `.env` is in `.gitignore`).

### Advanced Features
- **Memoization**: Enhanced performance with memoized components and selectors.
- **Multi-language Support**: Added optional multi-language features for a better user experience.
- **Bug Fixes**: Handled critical issues like improper page redirects and incorrect profile updates.

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- Firebase Account
- TMDB API Key
- OpenAI API Key

Deployment
The app is ready to be deployed using Firebase Hosting or any other platform that supports React apps.
