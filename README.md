DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=*local db table*
DB_USERNAME=root
DB_PASSWORD=admin

tables{
    animals{
        id,
        animal, (dog, cat) *
        img
    }
    types{
        id,
        kind, (dog, cat) *
        breed, (pet_dog, guard_dog || Savannah, Colorpoint Shorthair )
        img
    }
}

*sahlo folina*


:D:D:D:D:D:D::DD