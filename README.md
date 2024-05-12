# Website Time Tracker Chrome Extension

This Chrome extension tracks the time spent on different websites and sends the data to a Ruby on Rails server for analysis.

This project aims to promote productivity and mindful internet usage by providing a Chrome extension that tracks time spent on websites, allows users to set time limits and restrictions on distracting sites, and offers personalized dashboards with analytics for users to monitor and manage their online activities efficiently. By enabling users to gain insights into their browsing habits and take control of their time online, the extension encourages a more balanced and focused approach to internet usage, ultimately enhancing productivity and well-being in today's digital landscape.

## Features

- Tracks time spent on each website.
- Sends tab data to a Ruby on Rails server every 5 seconds.
- Calculates and formats the duration of time spent on each website.
- Provides a dashboard interface to visualize the time spent on websites.

## Installation

1. Clone this repository to your local machine.
2. Open Google Chrome and go to `chrome://extensions`.
3. Enable "Developer mode" in the top right corner.
4. Click on "Load unpacked" and select the directory where you cloned the repository.

## Usage

1. Once the extension is installed, click on the extension icon in the Chrome toolbar to open the dashboard.
2. The dashboard will display the time spent on each website in a list format.
3. The extension will automatically send tab data to the server every 5 seconds.

## Server Integration

To integrate the extension with your Ruby on Rails server, you'll need to set up an endpoint to receive and handle the tab data sent by the extension. The extension sends tab data as JSON objects containing the tab ID, URL, and time spent.

Example JSON object sent by the extension:

```json
{
  "id": 123,
  "url": "https://example.com",
  "time": "2024-05-21T12:30:45.000Z"
}
```

# Website Time Tracker

This Chrome extension tracks the time spent on different websites and sends the data to a Ruby on Rails server for analysis.

## Ruby on Rails Setup

1. **Install Ruby**: Ensure you have Ruby installed on your system. You can install it using a version manager like RVM or rbenv.

2. **Install Rails**: Install the Ruby on Rails gem using the following command:  bundle install

3. **Create a New Rails Application**: Create a new Rails application using the following command.

4. **Set Up MySQL Database**: Configure your Rails application to use MySQL as the database by updating the `config/database.yml` file.

5. **Generate Scaffold**: Generate a scaffold for the data model you want to track in your Rails application.

6. **Run Migrations**: Run migrations to create the necessary database tables: rails db:migrate

7. **Start the Rails Server**: Start the Rails server using the following command: Rails Server


## MySQL Setup

1. **Install MySQL**: Install MySQL on your system. You can download and install it from the official MySQL website.

2. **Create a Database**: Use the MySQL command line or a GUI tool to create a new database for your Rails application.

3. **Configure Rails**: Update the `config/database.yml` file in your Rails application to specify the MySQL database settings.

4. **Test Connection**: Test the connection to the MySQL database by running your Rails application and performing database operations.


## Usage

1. Once the extension is installed, click on the extension icon in the Chrome toolbar to open the dashboard.
2. The dashboard will display the time spent on each website in a list format.
3. The extension will automatically send tab data to the server every 5 seconds.

**##Demo Video Link: https://drive.google.com/file/d/1PUwWsmU3u1w3GUBoZmIbaAjpej-CFlU0/view?usp=sharing

## Deployed App
http://sentry.aerial-ace.tech/

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

