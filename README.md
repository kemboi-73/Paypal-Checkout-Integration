# Django PayPal Checkout API

## Overview(Work on progress)

This Django project showcases the integration of PayPal Checkout API to facilitate seamless online payments. PayPal Checkout allows users to make payments using various methods, including credit cards and PayPal accounts.

## Features

- **Secure Payments**: Utilize PayPal's secure infrastructure for processing payments, ensuring the safety of user transactions.

- **Easy Integration**: Easily integrate the PayPal Checkout API into your Django project, reducing the complexity of handling payment processes.

- **Customizable**: Customize the payment flow to meet the specific needs and branding of your application.

- **Test Environment**: The project includes a test environment, allowing developers to simulate transactions and test the payment flow without making actual charges.

## Getting Started

### Prerequisites

Before getting started, ensure you have the following:

- Python (3.x recommended)
- Django (install using `pip install django`)
- PayPal Developer Account (for API credentials)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/django-paypal-checkout.git
   cd django-paypal-checkout
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure PayPal API credentials:

   - Create a [PayPal Developer Account](https://developer.paypal.com/).
   - Create a new app and obtain the client ID and secret.
   - Copy the `example.env` file to `.env`:

     ```bash
     cp example.env .env
     ```

   - Replace the `PAYPAL_CLIENT_ID` and `PAYPAL_SECRET_KEY` in the `.env` file with your actual credentials.

### Usage

1. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

2. Run the development server:

   ```bash
   python manage.py runserver
   ```

3. Visit [http://localhost:8000/](http://localhost:8000/) in your browser.

4. Navigate to the checkout page and complete a test payment using PayPal.

## Contributing

If you'd like to contribute to this project, please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [PayPal Developer Documentation](https://developer.paypal.com/docs/)

