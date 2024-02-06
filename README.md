# Beeptunes AI System

## Introduction
Beeptunes is launching an artificial intelligence system for music recommendations to users. This exercise is designed for beginner programmers.

## Input
The program's input consists of two sections: user and album. Each section has information provided in Yaml format.


## Code Structure
The solution includes functions for adding users, adding albums, and querying user preferences based on different parameters such as artist, genre, age, and city.
    

### Functions
- `add_user`: Adds a new user to the system with the provided information.
- `add_album`: Adds a new album to the system with the provided information.
- `query_user_artist`: Queries the number of songs a user has purchased from a specific artist.
- `query_user_genre`: Queries the number of songs a user has purchased from a specific genre.
- `query_age_artist`: Queries the total number of songs purchased by users of a specific age from a specific artist.
- `query_age_genre`: Queries the total number of songs purchased by users of a specific age from a specific genre.
- `query_city_artist`: Queries the total number of songs purchased by users from a specific city from a specific artist.
- `query_city_genre`: Queries the total number of songs purchased by users from a specific city from a specific genre.


## Usage
To use the provided functions, import them from the solution module and follow the examples provided in the sample test cases.

## Sample Test
A sample test case is provided in the `test_all` function within the `TestAll` class. This test case covers various scenarios, including user queries based on artists, genres, ages, and cities.

## Running Tests
To run the sample test case or add additional tests, execute the Python script with the testing framework of your choice (e.g., `unittest`).

```bash
python -m unittest -v solution.py


### Sample Input
```yaml
1
- name: ali
  age: 12
  city: bushehr
  albums:
    - bidad
    - blaze
2
- name: bidad
  singer: shajarian
  genre: classic
  tracks: 10
- name: blaze
  singer: ghorbani
  genre: pop
  tracks: 9
1
1 ali ghorbani

