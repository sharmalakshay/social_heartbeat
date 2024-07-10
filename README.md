# Social Heartbeat

Social Heartbeat is a tool that allows you to monitor activity across multiple social networks. Enter usernames and specify a number of days to check if any activity has been made within that timeframe. Supported platforms include Twitter, Instagram, Facebook, and LinkedIn.

## Features

- Check recent activity on multiple social networks
- Specify the number of days to monitor
- Simple command-line interface

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/sharmalakshay/social_heartbeat.git
    ```

2. Navigate to the project directory:

    ```sh
    cd social_heartbeat
    ```

3. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Set up API keys and tokens for each social network. Follow the instructions in the `docs/api-setup.md` file to configure your authentication.

2. Run the tool with your desired usernames and number of days:

    ```sh
    python social_heartbeat.py --twitter example_twitter_user --instagram example_instagram_user --facebook example_facebook_user --linkedin example_linkedin_user --days 7
    ```

## Configuration

Make sure to set up your API keys and tokens in a `.env` file in the root directory of the project. The file should look like this:

```plaintext
TWITTER_API_KEY=your_twitter_api_key
TWITTER_API_SECRET_KEY=your_twitter_api_secret_key
TWITTER_ACCESS_TOKEN=your_twitter_access_token
TWITTER_ACCESS_TOKEN_SECRET=your_twitter_access_token_secret

INSTAGRAM_ACCESS_TOKEN=your_instagram_access_token

FACEBOOK_ACCESS_TOKEN=your_facebook_access_token

LINKEDIN_CLIENT_ID=your_linkedin_client_id
LINKEDIN_CLIENT_SECRET=your_linkedin_client_secret
LINKEDIN_ACCESS_TOKEN=your_linkedin_access_token
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or suggestions, feel free to open an issue or contact me at lakshay0495@gmail.com.

---

Happy monitoring!

---
