# Salon Appointment Scheduler

This project is part of the freeCodeCamp Relational Database curriculum.  
It demonstrates how to build a Bash script that interacts with a PostgreSQL database to manage salon appointments.

## Files

- **salon.sql** – Database dump containing schema and seed data (customers, services, appointments).
- **salon.sh** – Bash script that:
  - Displays available services in the format `#) <service>`
  - Prompts for service ID, phone number, customer name (if new), and appointment time
  - Inserts new customers and appointments into the database
  - Outputs confirmation messages like:  
    `I have put you down for a cut at 10:30, Fabio.`

---

## Learning Outcomes

Through completing this project, I learned how to:

- **Design relational databases**: Create tables with primary keys, foreign keys, and constraints to enforce relationships between customers, services, and appointments.
- **Work with PostgreSQL**: Use `psql` commands to create databases, insert data, and query information directly from the terminal.
- **Automate workflows with Bash**: Write a script (`salon.sh`) that interacts with the database, handles user input, and produces dynamic output.
- **Apply input validation**: Ensure users select valid services and handle cases where customers are new or already exist in the database.
- **Use SQL dumps for portability**: Generate a `salon.sql` file with `pg_dump` to save and restore the database structure and data.
- **Follow project specifications**: Match exact wording and formatting required by automated tests, reinforcing attention to detail.
- **Integrate scripting and databases**: Connect Bash scripts with SQL queries to build a functional appointment scheduler.

This project strengthened my ability to combine **database design**, **shell scripting**, and **problem-solving** to meet real-world requirements.


---

##Example Usage

~~~~~ MY SALON ~~~~~
Welcome to My Salon, how can I help you?

1) cut
2) color
3) perm
4) style
5) trim

