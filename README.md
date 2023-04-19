# LAB 08 - Material UI

### Task 1 - Navigation

1. Install the [MUI](https://mui.com/) library in this repository
2. Use the App Bar component to create a navigation in `App.js`, with links to the `characters`, `episodes` and `locations` pages

### Task 2 - Style the characters pages

1. Use components from the MUI library to style the `Characters` and `CharacterDetail` components
2. The list should be using the `Card` component, and include the name and image of the character, it should also include a link to the detail page (Make sure to use the React Router link)
3. The detail should include the image as well, but the rest is up to your imagination
4. There is also an `<Outlet />` component to display comments, leave it as is for now, it's a different task

### Tasks 2 & 3 - Style the episodes and locations pages

1. Use components from the MUI library to style all the components(pages) in the `components` folder.
2. There should be a sidebar on the left side of the page, that shows the list of episodes or locations
3. Use the `NavLink` from React Router to link to a detail of each episode or location, and highlight the selected one
4. The detail is up to your imagination, but I suggest you include links to characters form the selected episode or location

### Task 4 - comments

1. On the character detail page, we also render the `CharacterComments` component
2. The comments are a simple array of strings, use components from the MUI library to style the comments
3. Style the form to add a new comment as well

### BONUS - creativity

1. You can earn extra point by being creative and making a nice looking app with the MUI library
