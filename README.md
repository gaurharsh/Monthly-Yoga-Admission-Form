
# Hi, I'm Harsh! 👋


## 🚀 💫 About Me:
🔭 I'm currently working on .....

💫 Microsoft Certified  AZ-900, AI-900 ,DP-900,	SC-900.

👉Having a depth knowledge of 𝐂 𝐚𝐧𝐝 𝐂++.

⚡Coding on 𝗗𝗔𝗧𝗔 𝗦𝗧𝗥𝗨𝗖𝗧𝗨𝗥𝗘, 𝐏𝐘𝐓𝐇𝐎𝐍.

💭 Ask me about Azure and AWS.

👯 I'm looking to collaborate on Open Projects.

🌱Knowledge of OS, DBMS, CN AND OOPS.

💥Fun fact


# Monthly-Yoga-Admission-Form

The "Monthly Yoga Admission Form" is a comprehensive web application designed to facilitate the enrollment process for monthly yoga classes. Developed using a combination of cutting-edge technologies, including Bootstrap for the frontend, Django for the backend, and SQL for the database, this project offers a seamless and user-friendly experience for individuals interested in joining yoga classes on a monthly basis.

Key Features:

Bootstrap-Powered Frontend: The frontend of the application leverages the Bootstrap framework to deliver a responsive, visually appealing, and intuitive user interface. Employing Bootstrap's components and styles ensures a consistent and mobile-friendly experience for users accessing the admission form across various devices.

Django Backend: The backend is built using Django, a high-level Python web framework, known for its robustness and efficiency. Django handles the core functionalities of the application, including user authentication, form submissions, data processing, and interactions with the database.

SQL Database Integration: The application uses SQL as the database management system, allowing efficient storage, retrieval, and management of user information, such as enrollment details, selected batches, and payment records. SQL provides a structured and organized approach to store and manage data securely.

Enrollment Process: Users within the age limit of 18-65 can enroll for the yoga classes via the admission form. They have the flexibility to choose from four batches per day: 6-7AM, 7-8AM, 8-9AM, and 5-6PM. Participants can select a batch for a particular month and switch to another batch in the following months.

Monthly Payment: Enrolled individuals are required to pay the monthly fee of 500/- Rs INR. The payment system allows users to make payments at any time during the month for the entire month's fee.

Technologies Used:

Frontend: Bootstrap for responsive and user-friendly UI/UX.
Backend: Django framework for efficient server-side logic and API endpoints.
Database: SQL for robust and structured data storage and retrieval.
The Monthly Yoga Admission Form stands as a testament to the utilization of modern technologies to create an accessible, secure, and streamlined enrollment process for yoga enthusiasts, ensuring a delightful user experience from start to finish.


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
 - [Admin Page](https://gaurharsh5590.pythonanywhere.com/admin/)
 


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


![logo](https://media4.giphy.com/media/m6pvmOSXuTEPaKFWBz/giphy.gif?cid=ecf05e47ki7flra1yb4ew0rf8fbr86jrqa198elnpvzghq3b&ep=v1_gifs_search&rid=giphy.gif&ct=ghttps://miro.medium.com/v2/resize:fit:1400/1*ycIMlwgwicqlO6PcFRA-Iw.png)

![Logo](https://inspector.dev/wp-content/uploads/2023/04/logo-python-django.png)


![Logo](https://miro.medium.com/v2/resize:fit:1400/1*ycIMlwgwicqlO6PcFRA-Iw.png)

![Logo](https://cdn.educba.com/academy/wp-content/uploads/2019/09/Database-in-SQL%E2%80%8B.png)

![Logo](https://www.bootstrapdash.com/blog/wp-content/uploads/2017/08/bootstrap-4-beta-whats-new.jpg)

![Logo](data:image/png;base64,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)










## Related

Here are some related projects

[Awesome README](https://github.com/gaurharsh)


## 🛠 Skills
   Python,Django,SQL database,Bootstrap,


## Run Locally

Clone the project

```bash
  git clone https://github.com/gaurharsh/Monthly-Yoga-Admission-Form
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Support

For support, email gaurharsh5590@gmail.com.

