## Database Structure
The database for the Mochi Ordering Web Application consists of the following key tables:

1. **Users**: Stores customer information such as name, email, password.
2. **Mochis**: Contains data about available Mochi products including name, description, and flavor.
3. **Orders**: Tracks customer orders with fields for total amount, status (pending, completed, canceled), and user reference.
4. **Payments**: Stores payment information related to orders.

This structure allows seamless management of user accounts, product listings, orders, and payments within the system.

## Tech Stack
- **Backend**: Node.js, Express.js, 
- **Database**: MySQL (using Sequelize and  Using relationships between tables.)

### Prerequisites
- Node.js
- MySQL
- Git
