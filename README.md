#PGLife#

# PG Life - Property Search & Management System

PG Life is a property management and search platform that allows users to browse, search, and book PG (Paying Guest) accommodations. Users can explore properties across various cities, check reviews, ratings, and find their perfect place to stay.


## Features
- **User Authentication:** Users can register, log in, and manage their profiles.
- **Search for PGs:** Users can search for properties by city and filter the results.
- **Property Listings:** Display PG properties with images, ratings, reviews, rent, and more.
- **Property Reviews & Ratings:** Users can submit reviews and rate properties they have stayed in.
- **Favorites (Like Button):** Users can mark properties they are interested in as favorites.
- **Testimonials:** Display user testimonials with star ratings and reviews for properties.
- **Responsive Design:** The website is fully responsive, optimized for mobile and desktop views.

## Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL
- Apache or any other web server that supports PHP
- Composer (optional, for dependency management)

### Steps
1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/pglife.git
    ```

2. Navigate to the project directory:

    ```bash
    cd pglife
    ```

3. Set up the database:
    - Create a database `pglife` in MySQL.
    - Import the SQL schema from the `database/schema.sql` file to set up the tables.
    - Adjust the database credentials in `includes/database_connect.php` (hostname, username, password, and database name).

4. Install required PHP dependencies (if needed):

    ```bash
    composer install
    ```

5. Launch the project by opening `index.php` in your web browser or by configuring it on a local server using XAMPP/WAMP.

## Usage
1. **Home Page**: Users can search for PG accommodations by city.
2. **City Pages**: Clicking a city will show available PG properties in that city.
3. **Property Page**: View property details, reviews, ratings, and rent. Users can submit their own reviews and ratings.
4. **Dashboard**: Users can manage their profiles, see their reviews, and view their favorite properties.

### Testing Features:
- **User Registration & Login**: Ensure you can register a new user and log in.
- **Property Search**: Check if searching by city and filtering works properly.
- **Favorites**: Test the like button to add/remove favorites.
- **Reviews & Ratings**: Add a review to a property and check if the rating system works.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP, MySQL
- **Database**: MySQL
- **Libraries**: 
    - FontAwesome (for icons)
    - jQuery (for AJAX functionality, if needed)
    - Bootstrap (for responsive layout)
 

  Some Snapshots
  


![Screenshot 2025-03-23 164219](https://github.com/user-attachments/assets/52c01563-049f-4a77-8b73-2ac4af780d2a)




![Screenshot 2025-03-23 164156](https://github.com/user-attachments/assets/bd68ad1a-68e9-4201-a0a3-318d145527d9)




Please feel free to let me know if you have any further revisions or specific changes you'd like to make.
