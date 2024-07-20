# POLIBOX

POLIBOX is a comprehensive platform designed to assist students of Gdańsk University of Technology (PG). This project, built using Django, provides various resources and tools to facilitate the academic journey of students.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Materials**: Find all educational aids and materials in one place.
- **Email Generator**: Check how to start an email to a specific lecturer and copy the template.
- **Calendar**: Stay updated with important dates such as colloquia, exams, and ceremonies.
- **Progress Tracker**: Monitor your academic progress.
- **Information**: Access contact information and the portal's regulations.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/polibox.git
    cd polibox
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply the migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser**:
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

## Usage

Once the server is running, you can access the application at `http://127.0.0.1:8000/`.

- **Materials**: Navigate to the `Materials` section to find study aids.
- **Email Generator**: Use the `Generator` to create email templates.
- **Calendar**: Check the `Calendar` for important academic dates.
- **Progress Tracker**: View your progress in the `Progress` section.
- **Information**: Visit the `Information` page for contact details and regulations.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add feature"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request.

Please ensure your code adheres to the existing style and includes appropriate tests.

## License

This project is licensed under the BSD-2 License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any queries, suggestions, or feedback, please contact:

- **Michał Sadkowski**: [msadkowski000@gmail.com](mailto:msadkowski000@gmail.com)
- **GitHub**: [github.com/m-sadkowski](https://github.com/m-sadkowski)

---

Thank you for using POLIBOX! We hope it makes your academic journey easier and more efficient.
