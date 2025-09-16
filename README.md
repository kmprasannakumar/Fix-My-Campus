
# Fix My Campus

This web application enables students, staff, and administrators to report, track, and resolve infrastructure and facility issues across the institution. The platform provides a user-friendly interface for submitting problems related to electricity, water, internet, furniture, cleanliness, and more.


## Features

- **User Authentication**: Secure login/signup system with password recovery
- **Issue Reporting**: Submit detailed reports about institution infrastructure problems
- **Issue Tracking**: Track the status of reported issues (Pending, In Progress, Resolved)
- **User Profiles**: View and update personal information
- **Dashboard**: Visual analytics of institution-wide issues
- **Admin Panel**: Comprehensive management system for administrators
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop devices


## Technical Stack

- **Backend**: Python Flask
- **Database**: MySQL
- **Frontend**: HTML, Tailwind CSS, JavaScript
- **Charts**: Chart.js
- **Icons**: Font Awesome


## Directory Structure

```
admin.py
app.py
requirements.txt
static/
  css/
    styles.css
  js/
    main.js
    charts.js
templates/
  layouts/
    base.html
  components/
    navbar.html
    footer.html
  admin/
    dashboard.html
    login.html
    manage_issues.html
    user_management.html
    audit_logs.html
  login.html
  signup.html
  forgot_password.html
  home.html
  profile.html
  change_password.html
  report_issue.html
  my_issues.html
  issue_dashboard.html
  about_campus.html
  help_support.html
  about.html
```

## Contact

For queries or support, please contact the institution's administration office.

## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/fix-my-campus.git
cd fix-my-campus
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the application:
```
python app.py
```

4. Run the admin panel (separate server):
```
python admin.py
```

## Database Setup

The application is configured to use a MySQL database. The database connection details are set in the app.py file:

```python
app.config['MYSQL_HOST'] = 'sql12.freesqldatabase.com'
app.config['MYSQL_USER'] = 'sql12774989'
app.config['MYSQL_PASSWORD'] = 'acxEkHFzcu'
app.config['MYSQL_DB'] = 'sql12774989'
```

## User Credentials

For testing purposes:

- **Regular User**:
  - Create a new account through the signup page

- **Admin**:
  - Username: admin@1234
  - Password: 123

## License

This project is licensed under the MIT License - see the LICENSE file for details.