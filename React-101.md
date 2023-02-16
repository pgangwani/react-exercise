## Coding Exercise

In this exercise, you'll be building a simple React app that fetches data from an API and displays it in a table. Your app should have the following features:

- Display a loading spinner while the data is being fetched
- Display an error message if the data cannot be fetched
- Display the fetched data in a table with columns for `id`, `name`, and `email`
- Allow the user to filter the table by name or email
- Allow the user to sort the table by any column

### Requirements

- Use React for the UI
- Use a library like Axios or `fetch` to fetch data from an API
- Use a library like Lodash or Underscore for filtering and sorting
- Write tests for your components and any utility functions you create

### API

Use the following endpoint to fetch data:

https://jsonplaceholder.typicode.com/users

### Example

Here's an example of what the app might look like:

![Example App](https://i.imgur.com/M97HkzI.png)

### Submission

Please submit your solution as a GitHub repository or a ZIP file. Make sure to include instructions on how to run your app and your tests.





### Suggestion for Solving the Exercise (Only use if you are really unsure and honest to yourself)

To start, you can create a new React app using a tool like `create-react-app`. You can then build the components and functionality required by the exercise.

Here's an outline of one possible approach to the exercise:

1. Create a `Table` component that will display the fetched data in a table format with columns for `id`, `name`, and `email`. This component should accept a `data` prop, which is an array of objects that contain the data to be displayed in the table.

2. Create a `Spinner` component that displays a loading spinner while the data is being fetched. You can use a library like `react-spinners` to easily create a spinner component.

3. Create an `Error` component that displays an error message if the data cannot be fetched.

4. Create a `Filter` component that allows the user to filter the table by name or email. This component should accept a `data` prop, which is an array of objects that contain the data to be filtered.

5. Create a `Sort` component that allows the user to sort the table by any column. This component should accept a `data` prop, which is an array of objects that contain the data to be sorted.

6. Use a library like Axios or `fetch` to fetch data from the API endpoint.

7. Use a library like Lodash or Underscore for filtering and sorting the data.

8. Write tests for your components and any utility functions you create using a testing library like Jest.

9. Combine all the components and functionality to create the final app.

Once you have built the app, you can submit your solution as a GitHub repository or a ZIP file. Make sure to include instructions on how to run your app and your tests.

> *Credits goes to [ChatGPT](https://chat.openai.com/) :heart_eyes: for helping me write this excercise for you. Please dont ask it the answer :wink:* 
