# IVR-with-Twilio-CodeIgniter-and-Ngrok
Interactive Voice Response System with Twilio, CodeIgniter and Ngrok

## Requirements
1. [Twilio](https://www.twilio.com/) Account.
2. Linux OS (feel free to use any OS).
3. [Git](https://git-scm.com/).
4. [Composer](https://getcomposer.org/).
5. [PHP](https://www.php.net/).
6. [Ngrok](https://ngrok.com/).

## Installation
#### Install the Project Requirements:

```bash
sudo apt-get install php git composer -y
```

```bash
snap install ngrok
```
#### Clone the project on GitHub:

```bash
git clone https://github.com/learningdollars/adeoluwaakinsanya-IVR-with-Twilio-CodeIgniter-and-Ngrok.git
```

## Usage
Navigate to the project directory in your terminal and start your PHP local web server

```bash
php -S localhost:8000
```
Open a new terminal, Navigate to the project directory and start your Ngrok Server

```bash
ngrok http 8000
```
Create a Twilio account and set up webhooks to your phone number using the Ngrok generated URL.



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://github.com/learningdollars/adeoluwaakinsanya-IVR-with-Twilio-CodeIgniter-and-Ngrok/blob/master/LICENSE)