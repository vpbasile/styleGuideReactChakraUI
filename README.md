# React Style Guide
My personal style guide for react apps

1. **Naming Conventions:**
   - a. Use camelCase for variables, functions, and component names.
   - b. Use PascalCase for component names (React components).
   - c. Use UPPERCASE_SNAKE_CASE for constants.
   - d. Use lowercase for file and folder names, and use hyphens to separate words in file names (kebab-case).

2. **State Management:**
   - a. When using `useState`, the setter function name should start with "SET" followed by the state name in camelCase. Example: `const [state, SETState] = useState("init")`.

3. **Component Structure:**
   - a. Keep your components focused and single-responsibility. This improves maintainability and reusability.
   - b. Components that represent pages should be placed in a `pages` directory (Next.js convention).

4. **Imports:**
   - a. Group imports in the following order: external libraries/modules, internal modules/components, styles.
   - b. Use absolute imports for internal modules to improve readability and prevent relative path issues.

5. **Commenting and Documentation:**
   - a. Document important functions and components using JSDoc or a similar style.
   - b. Use comments to explain complex logic, edge cases, or any non-obvious code behavior.
   - c. Use component templates so that each component has a similar, readable structure.

6. **CSS and Styling:**
   - a. Use Tailwind CSS for styling React components (or other preferred styling approach).
   - b. Keep your styles modular and close to the components they are associated with.

7. **SQL Table Names:**
   - a. Use singular nouns for SQL table names. Example: "purchase" instead of "purchases".

8. **File Organization:**
   - a. Organize your project files based on their functionality (components, pages, utilities, styles, etc.).
   - b. Keep related files together within their respective directories.

9. **Error Handling:**
    - a. Implement proper error handling in asynchronous code, including API calls and database interactions.

10. **Version Control:**
    - a. Utilize Git and GitHub to track changes, collaborate with team members, and manage version control.

11. **Testing:**
    - a. Write tests for critical components and functions using a testing library like Jest and testing utilities for React.

12. **Data Handling and Structures:**
    - a. For collections of rectangular data that have a name, prefer using maps rather than arrays or simple objects. Maps provide better key-based access and are more suitable for structured data.

13. **Data Structure and Demonstration:**
    - a. When creating a new data structure, accompany it with an SQL file that creates all necessary tables, defines relationships, and includes dummy data. This enables easy demonstration and testing of the data structure's functionality.
