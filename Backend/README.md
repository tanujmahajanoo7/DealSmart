# DealSmart Backend

Backend API and server implementation for the DealSmart application.

## Structure

```
Backend/
├── DealSmartBackend/    # Main backend application code
└── DealSmartdump.sql    # Database dump file
```

## Database

The `DealSmartdump.sql` file contains the database schema and initial data.

### Importing the Database

1. Create a new database (e.g., `dealsmart`)
2. Import the dump file:
   ```bash
   mysql -u username -p dealsmart < DealSmartdump.sql
   ```
   Or for PostgreSQL:
   ```bash
   psql -U username -d dealsmart -f DealSmartdump.sql
   ```

## Setup Instructions

1. Navigate to the `DealSmartBackend/` directory
2. Install dependencies (check the specific README in DealSmartBackend/)
3. Configure database connection in environment variables or config files
4. Run the backend server

## Environment Variables

Configure the following environment variables:

- Database connection settings
- API port
- Authentication secrets
- Other service configurations

## API Documentation

[Add API documentation links or details here]

## Running the Backend

[Add specific commands to run the backend server]

## License

[Add your license information here]

