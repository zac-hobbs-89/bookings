# README

- Dependencies

  Both apps need to be in the same folder on your machine.

  - API:

    - rspec for testing.
    - faker to mock data in seed file and tests.

    From the api directory run `bundle`/`bundle install` to install the required gems.

  - React-app:

    - react-testing-library for testing.
    - moment for date/time formatting.
    - material UI components and styling.

    From the react-app directory run `npm install` to install all dependencies there also.

- Database creation & initialization

  Run `rails db:create && rails db:migrate && rails db:seed`

- To run the app:

  To run the app using heroku locally from the api directory, just run:

  `heroku local -f Procfile.dev`
# bookings
