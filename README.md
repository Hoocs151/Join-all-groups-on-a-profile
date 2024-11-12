# Join All Groups on a Steam Profile

This is a Tampermonkey script that automatically joins all public groups of a Steam profile. Once installed, it will allow you to join every public group a person is part of with just a few clicks. It's designed to work seamlessly with Steam community profiles.

## Features
- Join all public groups on a Steam profile automatically.
- Fast and efficient with concurrent requests to join groups.
- Simple to use and easy to install.

## Installation

1. Install **Tampermonkey** extension for your browser:
   - [Chrome](https://chrome.google.com/webstore/detail/tampermonkey)
   - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
   - [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey)

2. After installing Tampermonkey, click the Tampermonkey icon in your browser and select "Create a new script...".

3. Delete the default code and paste the script from this repository.

4. Save the script.

Alternatively, you can directly install the script from [GreasyFork](https://greasyfork.org/vi/scripts/516934-join-all-groups-on-a-profile).

## Quick Usage Guide

1. Go to any Steam profile (either through a custom URL or Steam ID).
2. Press **F5** or **CTRL+R** to refresh the page.
3. Wait a few seconds for the script to join all public groups automatically.
4. If some groups are not joined, refresh the page again and wait for the process to complete.

That's it! The script will automatically join all public groups the profile belongs to.

## How It Works

The script sends a series of requests to join all the groups listed on the Steam profile. The requests are made concurrently (in parallel), allowing for a faster join process. The script will attempt to join each group the user is a part of, and log success or failure for each attempt.

## Troubleshooting

- If you notice some groups are not joined, try refreshing the page a few more times.
- Make sure the Steam profile is public and accessible.

## Contributing

Feel free to open an issue or submit a pull request if you want to improve or modify the script. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
