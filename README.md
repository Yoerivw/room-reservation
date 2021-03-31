# room-reservation

## App requirements
    --user login
        --User can:
            -edit, delete details
            -login / logout
            -view reservations
            -look at rooms available
            -book a room if available
        --Different types of user models ( add later)
        
        


## DATABASE
    --Create new database
    --create tables according to specification
        --Users
            -id int 
            -first_name char
            -last_name
            -email
            -user_name
            -password
            -priviledges
        --Rooms
            -id int
            -roomName varchar(255)
            -availability
    --Connect database to front end

## VIEWS
    --Build out:
        -User registration form
        -User Settings page to edit or delete account
        -Home Page
        -Single Room Page
        -Availability calendar

## ROUTES / CONTROLLERS
    --Set up Routing
        - '/' => 'home'
        - '/register' => 'registration page'
        - '/rooms' => 'All rooms'
        - '/rooms/name' => 'individual room name'
        - '/rooms/name/book' => 'book a room that is available'

