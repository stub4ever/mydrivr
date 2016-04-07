
# 1: Planning

  Who is this application for?

    I build A user personal driver platform. A place where users can find and book their favorite driver in a certain city.

  What do we want to accomplish?

    Strong engagement between users and driver. The driver deliver customer experience that potential users never leave them.
    This app is the best drive experience for the user in the world!

  What features do we want?

      Signup / Signin
        facebook api
        google api
        devise
        mailer

      - Search
        Simple search
        Elasticsearch?

      - Bookings

      - Profiles
        Create / Edit / Destroy
        rating / review
        hour rates
        GEO api?

      - Driver
        accept / denied
        booking management

      - User
        cancel booking
        request call
        add favorite driver

      - Cities
          Create / Edit / Destroy

      - Contact
          Contact form
          Sendgrid

  User Stories

    - As a visitor, I want to explore my current city to find my driver
    - As a visitor, I want to see which country
    - As a visitor, I want to read more information about the company mydrivr
      to understand what the company stands for
    - As a visitor, I want send the company a message for any feedback
    - As a visitor, I can signup/login
      so that I can become an User
      so that I can become an Driver

    - As a user, I want more information about the driver
      so that I know if the the hour rates worth base on review/rating
      so that I send driver a message
      so that I am able make an request to let the driver call me
    - As a user, I can add an booking
    - As a user, I see the booking dashboard
      so that I can cancel the booking
      so that I can see previous or current booking
    - As a user, I can add an review
      so that I can share my trip experience

    - As a driver, I want to see information of the user who has booking me
    - As a driver, I want able to cancel or accept the booking
    - As a driver, I want to edit or destroy my profile
      so that I can change my bio
      so that I can change hour rates
      so that I can change contact information
    - As a driver, I want to manage my booking
      So that I cancel or accept the booking
      So that I can see the history of the booking
      So that I can see my total earning


# 2: Model our data

  User
  -
  Booking
  -
  Country
  -
  City
  -
  Trip
  -
  Review
  -

# 3: Pages & Routes

| url           | routes             |
| ------------- |:------------------:|
| /             | pages#home         |
| /             | pages#about        |
| /             | pages#contact      |
| /city/:id     | cities#show        |
| /             |                    |
| /             |                    |



