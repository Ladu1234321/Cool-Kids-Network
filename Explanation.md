# Explanation

## Overview
This file contains an explanation of the project and its components.

## File Structure
- `index.php`: This file is the main entry point for the WordPress theme.
- `functions.php`: Contains all the custom functions for the theme.
- `style.css`: The stylesheet for the theme.
- `login.php`: Custom login page logic.

## Important Functions
- `cool_kids_set_role()`: This function sets user roles based on specific conditions.
- `wp_set_auth_cookie()`: Used for setting authentication cookies upon login.

## REST API
The project includes a custom REST API endpoint `/cool-kids/v1/set-role/` that allows role changes via POST requests.

## User Roles
- `cool_kid`
- `cooler_kid`
- `coolest_kid`

## Special Features
- Custom character generation for new users.
- Access control based on user roles.

## Known Issues
- Header errors when using `wp_redirect()` after setting cookies.

## Future Improvements
- Implement more robust error handling.
- Refactor the code to support multiple roles more effectively.
