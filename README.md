# Monthly-Yoga-Admission-Form

The "Monthly Yoga Admission Form" is a comprehensive web application designed to facilitate the enrollment process for monthly yoga classes. Developed using a combination of cutting-edge technologies, including Bootstrap for the frontend, Django for the backend, and SQL for the database, this project offers a seamless and user-friendly experience for individuals interested in joining yoga classes on a monthly basis.

Key Features:

Bootstrap-Powered Frontend: The application's front end leverages the Bootstrap framework to deliver a responsive, visually appealing, and intuitive user interface. Employing Bootstrap's components and styles ensures a consistent and mobile-friendly experience for users accessing the admission form across various devices.

Django Backend: The backend is built using Django, a high-level Python web framework, known for its robustness and efficiency. Django handles the core functionalities of the application, including user authentication, form submissions, data processing, and interactions with the database.

SQL Database Integration: The application uses SQL as the database management system, allowing efficient storage, retrieval, and management of user information, such as enrollment details, selected batches, and payment records. SQL provides a structured and organized approach to store and manage data securely.

Enrollment Process: Users within the age limit of 18-65 can enroll for the yoga classes via the admission form. They have the flexibility to choose from four batches per day: 6-7 AM, 7-8 AM, 8-9 AM, and 5-6 PM. Participants can select a batch for a particular month and switch to another batch in the following months.

Monthly Payment: Enrolled individuals are required to pay a monthly fee of 500/- Rs INR. The payment system allows users to pay any time during the month for the entire month's fee.

Technologies Used:

Frontend: Bootstrap for responsive and user-friendly UI/UX.
Backend: Django framework for efficient server-side logic and API endpoints.
Database: SQL for robust and structured data storage and retrieval.
The Monthly Yoga Admission Form is a testament to modern technologies' utilization to create an accessible, secure, and streamlined enrollment process for yoga enthusiasts, ensuring a delightful user experience from start to finish.


## Features

- User Registration and Authentication:
- Admission Form
- Batch Selection
- Admin Dashboard
- Database Management
- Responsive UI Design
- Error Handling and Validation
- Payment Integration (Mocked)
- Notification System:


## Acknowledgements

 - [Monthly Yoga Admission Form](https://gaurharsh5590.pythonanywhere.com/)
 - [Admin Page]([https://github.com/matiassingers/awesome-readme](https://gaurharsh5590.pythonanywhere.com/admin/))
 


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## ER Diagram for Yoga Class Admission Form:
Entities:

User:

Attributes:
user_id (primary key)
first_name
last_name
email (unique)
phone_number
date_of_birth
address
Membership:

Attributes:
membership_id (primary key)
user_id (foreign key references User.user_id)
start_date
end_date
is_active
current_batch
Batch:

Attributes:
batch_id (primary key)
start_time
end_time
max_capacity
Relationships:

One User can have one Membership: A user can only have one active membership at a time, represented by a one-to-one relationship between User and Membership.
One Membership belongs to one User: Each membership record is associated with a specific user through the foreign key reference.
One Membership has one Batch: A member can only choose one batch in a month, represented by a one-to-one relationship between Membership and Batch.
One Batch can have many Memberships: Multiple members can choose the same batch in a month.
Additional Notes:

The is_active attribute in Membership can be used to mark expired or cancelled memberships.
The current_batch attribute in Membership stores the ID of the currently assigned batch for a member.
You can also add additional attributes to entities as needed, such as payment details or instructor information.
This ER diagram provides a basic structure for the database design and can be further refined based on specific requirements. Remember to consult your team and consider additional functionality like membership renewals, attendance tracking, and more complex scheduling functionalities as you continue development.


## Documentation

[Documentation](https://docs.google.com/document/d/1MXwFCMk2pPWusw-eSyWEBFzFSUk08uCl/edit?usp=sharing&ouid=113066214093844739692&rtpof=true&sd=true)


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## Related

Here are some related projects

[Awesome README](https://github.com/gaurharsh)


## Roadmap

- Additional browser support

- Add more integrations


## 🛠 Skills
   Python,Django,SQL database,Bootstrap,


