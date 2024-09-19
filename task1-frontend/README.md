<h1 align="center">Task 01: Contact Management Application</h1> 

**Objective**: Build a React application that displays contacts and implements filtering and sorting.

## Instructions

1. **Create a React Application**:
   - Create a React component named `ContactList`.
   - This component will display all the contacts.
   - Implement sorting and filtering within this component.
   - Use the `useState` and `useEffect` hooks as needed.

2. **Fetch Contacts**:
   - Fetch a list of contacts from a provided API endpoint or use a mock JSON file for this.

3. **Display Contacts**:
   - Display the contacts in a list format.
   - Each contact should display the following information
      - name
      - email
      - mobile

4. **Implement Filtering**:
   - Implement search functionality that filters the contacts based on the text entered by the user.
   - Create a dropdown or toggle feature to switch between different filter types:
     - **Filter by Name**: The search input will filter contacts by matching the name field.
     - **Filter by Email**: The search input will filter contacts by matching the email field.
     - **Filter by Mobile  Number**: The search input filters contacts by matching the number field.
   - When the user switches between these filter types, the search behavior should update accordingly.
   - Ensure the list dynamically updates as the user types or changes the filter type.

5. **Sorting**:
   - Implement a sorting option that allows the user to sort the contacts alphabetically by name, email
   - Sorting should happen in both **ascending** and **descending** order.
     - **Sort by Name**
     - **Sort by Email**
   
### Setup Instructions

1. Navigate to the `task1-frontend` directory.
2. Install dependencies: `npm install`.
3. Start the development server: `npm start`.

### Evaluation Criteria

- Proper use of React hooks (`useState`, `useEffect`).
- Correct implementation of filtering with toggle for filtering by name, email, and mobile number.
- Correct implementation of sorting with dropdown for sorting by name and email.
- Code readability and organization.

### Provided Mock Data. Add More.

```json
[
  {
    "id": 1,
    "name": "John Doe",
    "email": "john.doe@example.com",
    "mobile": 1234567890
  },
  {
    "id": 2,
    "name": "Jane Smith",
    "email": "jane.smith@example.com",
    "mobile": 9876543210
  },
  {
    "id": 3,
    "name": "Alice Johnson",
    "email": "alice.johnson@example.com",
    "mobile": 5555555555
  }
]
```