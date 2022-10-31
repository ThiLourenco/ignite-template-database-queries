## DATABASE - queries

#### UsersRepository
- [x] findUserWithGamesById
- [x] findAllUsersOrderedByFirstName
- [x] findUserByFullName

#### GamesRepository
- [x] findByTitleContaining
- [x] countAllGames
- [x] findUsersByGameId

### Específicação dos testes

#### UsersRepository
- [x] Should be able to find user with games list by user's ID
- [x] Should be able to list users ordered by first name
- [x] Should be able to find user by full name

#### GamesRepository
- [x] Should be able find a game by entire or partial given title
- [x] Should be able to get the total count of games
- [x] Should be able to list users who have given game id

## :computer: Install ##

```bash
# Clone this repository
$ git clone https://github.com/Thifany-Nicastro/IgniteNode-ChapterIII-Desafio01.git

# Entry folder 
$ cd IgniteNode-ChapterIII-Desafio01

# Install dependence
$ yarn ou yarn install

# Run All Tests
$ yarn dev

```