Airbnb Clone Backend Use Case Diagram
Overview
The use-case-diagram/ directory contains documentation and visualization for the use case diagram of the Airbnb Clone backend, as part of the alx-airbnb-project-documentation repository. The diagram illustrates interactions between actors (Guest, Host, Admin, System) and the system for key functionalities like user registration, property booking, and payments.
Files

use_case_diagram.md: A Markdown document detailing the actors, use cases, relationships, and instructions for creating the use case diagram in Draw.io.
use_case_diagram.png: A PNG file exported from Draw.io, visualizing the use case diagram.

Purpose
The use case diagram captures how different actors interact with the Airbnb Clone backend, based on the features in features-and-functionalities/features.md. It includes:

Actors: Guest, Host, Admin, and System.
Use Cases: User registration, login, profile management, property listing management, search/filtering, booking, payments, reviews, notifications, and admin dashboard functions.
Relationships: Associations, includes, and extends to show dependencies and optional actions.

Usage

Review Use Cases:
Open use_case_diagram.md to understand the actors, use cases, and relationships.
Use the document to guide backend development and ensure all interactions are implemented.


Visualize Diagram:
View use_case_diagram.png to see the use case diagram.
Use Draw.io to edit the diagram if needed (import the PNG or recreate from use_case_diagram.md).


Implementation:
Align development with the MySQL schema in database-script-0x01/schema.sql.
Test functionalities using sample data in database-script-0x02/seed.sql.
Refer to features-and-functionalities/features.md for feature details.



Draw.io Instructions
To recreate or edit the use_case_diagram.png:

Open Draw.io (diagrams.net) and select a blank diagram.
Draw a rectangle labeled "Airbnb Clone Backend" as the system boundary.
Add stick figures for Guest, Host, and Admin outside the boundary.
Add ovals for each use case (e.g., "Create Booking") inside the boundary.
Connect actors to use cases with solid lines for associations.
Use dashed arrows for <<include>> (e.g., Create Booking to Process Payment) and <<extend>> (e.g., Cancel Booking to Create Booking).
Export the diagram as a PNG named use_case_diagram.png.
Store the file in the use-case-diagram/ directory.

Notes

Database: The backend uses MySQL with CHAR(36) for IDs and VARCHAR with CHECK constraints for restricted values, as defined in database-script-0x01/schema.sql.
Visualization: The use_case_diagram.png is a static export. Recreate in Draw.io using use_case_diagram.md for modifications.
Repository: Commit and push use_case_diagram.md and use_case_diagram.png to the use-case-diagram/ directory in the alx-airbnb-project-documentation repository.git add use-case-diagram/
git commit -m "Add use case diagram and documentation for Airbnb Clone backend"
git push origin main


Dependencies: Ensure the MySQL database is set up with the schema before testing use cases.

For feature details, see features-and-functionalities/README.md. For schema, see database-script-0x01/README.md. For sample data, see database-script-0x02/README.md.