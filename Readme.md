# Employee Salary Plugin

The Employee Salary Plugin is a WordPress plugin that allows administrators to manage employee salary records and
enables employees to search for their salary details. The plugin calculates tax and net salary based on provided tax 
brackets and displays the results in a user-friendly format.

## Features

- Admin interface for adding, editing, and deleting employee salary records.
- Front-end form for employees to search for their salary details.
- Displays employee number, month, salary, tax, and net salary.
- Calculates tax and net salary based on defined tax brackets.

## Installation

1. **Download the Plugin**: Clone or download the repository.

2. **Upload to WordPress**:
    - Create a folder named `employee-salary-plugin` in the `wp-content/plugins` directory of your WordPress installation.
    - Copy the `employee-salary-plugin.php` file into the `employee-salary-plugin` folder.

3. **Activate the Plugin**:
    - Go to the WordPress admin dashboard.
    - Navigate to Plugins > Installed Plugins.
    - Find the "Employee Salary Plugin" and click "Activate".

4. **Database creation**:
    - The plugin automatically creates a custom table in the database to store employee salary records upon activation.

## Usage

### Admin Interface

1. **Access Admin Page**:
    - Go to the WordPress admin dashboard.
    - Navigate to Employee Salaries > Employee Salaries.

2. **Add Employee Salary**:
    - Fill in the employee number, month, and salary.
    - Click "Add Salary".

3. **Edit Employee Salary**:
    - Find the employee record you wish to edit.
    - Update the employee number, month, or salary as needed.
    - Click "Update".

4. **Delete Employee Salary**:
    - Find the employee record you wish to delete.
    - Click "Delete" and confirm the deletion.

### Front-End Form

1. **Embed Shortcode**:
    - Add the `[employee_salary]` shortcode to any page or post where you want the search form to appear.

2. **Search Salary**:
    - Enter the employee number in the search form.
    - Click "Search Salary".
    - The results will display the employee number, month, salary, tax, and net salary.

## Tax Calculation

The plugin calculates tax based on the following tax brackets:

| Income Range          | Tax Rate |
|-----------------------|----------|
| $0 - $1,500           | 0%       |
| $1,501 - $3,750      	| 16%      |
| $3,751 - $11,250   	| 30%      |
| $11,251 - $15,800    	| 37%      |
| $15,801 and over      | 45%      |

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Author

Muskan Sidana