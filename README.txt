# Shauna Roper Rocket Launch Explorer

## https://github.com/sr928400/Rocket_Launch_Explorer.git

### In the callback version the getUpcomingLaunches function receives populateDropdown as a parameter. When the API finishes returning the launch data the callback function runs and fills the dropdown with the launch names.  When a launch is selected another callback is used to display the details for that launch.
### In the Axios version I replaced XMLHttpRequest with Axios. The .then() method runs when the request is successful and handles the data that is returned from the API. The .catch() method runs if there is an error and displays an error message for the user.
