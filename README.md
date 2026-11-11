# Employee-Management-System
Designed a secure database layer using PreparedStatement, validation, exception handling, and multi-field search functionality.

. Developed a CRUD employee management system in Java with a DAO pattern and JDBC persistence layer, separating model,
service, and data-access responsibilities into distinct packages.
. Wrote parameterized SQL using PreparedStatement across all create, read, update, and delete paths to prevent SQL injection,
with try-with-resources guaranteeing connection, statement, and result-set cleanup.
. Modeled an Employee/Manager inheritance hierarchy with polymorphic behavior and an employee_type discriminator column,
persisting subtype-specific fields through a single reusable DAO.
. Designed a 9-column MySQL schema with AUTO_INCREMENT primary key and UNIQUE email constraint, and added servicelayer validation (regex email matching, positive-salary rules) plus multi-field keyword search across name, email, department, and designation.
