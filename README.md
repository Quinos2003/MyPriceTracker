# MyPriceTracker

MyPriceTracker is a price tracking application that allows you to monitor the prices of products on various e-commerce websites. The application uses web scraping to extract the relevant information from the websites and displays it in a user-friendly interface.

## Technologies Used

- Python 3.8
- Django 3.2
- Beautiful Soup 4
- Celery 5.0
- Redis 6.2
- Bootstrap 5
- JavaScript
- HTML
- CSS

## Installation

1. Clone the repository:
git clone https://github.com/Quinos2003/MyPriceTracker.git

2. Install the dependencies:
cd MyPriceTracker
pip install -r requirements.txt

3. Create a database:
python manage.py migrate

4. Run the development server:
python manage.py runserver

5. Open the application in your web browser:
http://localhost:8000/

## Usage

1. Register for a new account or login with your existing account.
2. Add the URLs of the products you want to track and select the websites from the dropdown list.
3. The application will automatically scrape the prices of the products at regular intervals and display them in the dashboard.
4. You can view the price history of each product and set up email notifications for price drops.

## Contributing
Contributions are welcome! If you would like to contribute to the project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
