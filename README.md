# Blood Bank Network Management System

Welcome to the Blood Bank Network Management System project! This system aims to digitize the process of acquiring blood for ourselves or our relatives. Say goodbye to standing in queues and reserve your blood with a single click.


## Features

The Blood Bank Network Management System offers the following features:

### Home Page

- Provides an overview of the system.
- Includes a user-friendly navigation menu.

### User Dashboard

- Displays the user's dashboard with buttons for navigation.
- Shows the user's wallet balance.

### Hospitals and Donation/Receival

- Allows users to select hospitals when donating or receiving blood.
- Displays hospitals based on the selected city.

### Donation Transaction Registration

- Provides a form for users to register donation transactions.
- Collects necessary details for the transaction.

### Blood Availability

- Shows the availability of blood at selected hospitals.

### Transaction ID

- Generates a unique transaction ID for each transaction.
- Enables users to refer to the transaction ID for further procedures.

### Transaction History

- Displays the history of transactions made by the user.

### Admin Dashboard

- Provides an administrative dashboard with various features.
- Allows closing transactions and suggests payment methods if required credit is not available.
- Automatically deducts payment from the user's wallet if available.
- Adds credit to the user's wallet when a donation transaction is closed.
- Updates blood stock after closing a transaction.
- Manages user accounts.
- Generates a receipt after closing a transaction.

### Employee Dashboard

- Enables employees to update blood data when new stock is not available through the portal.
- Allows employees to close transactions with similar features as mentioned above.

## Tech Stack

**Front-End:** HTML, CSS, Bootstrap, JavaScript

**Server:** C#, ASP.NET Core MVC, SQL

## Setup and Installation

To run the Blood Bank Network Management System locally, follow these steps:

1. Clone the project repository from GitHub.
2. Open the project in Visual Studio.
3. Make changes to the Connection String in the appsettings.json file.
4. Add a migration for the creation of the database automatically by running the following command in the Package Manager Console:

```
add-migration mymigration
```

5. Update the database by running the following command in the Package Manager Console:

```
update-database
```

6. Start the local web server and navigate to the website's URL.
7. You should now be able to access and interact with the Blood Bank Network Management System.





