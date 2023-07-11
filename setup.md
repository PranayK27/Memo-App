xcode-select --install
brew tap mongodb/brew 
brew update
brew install mongodb-community@6.0
brew --prefix
brew services start mongodb-community@6.0
brew services stop mongodb-community@6.0

POST: http://localhost:4000/todos
{
"name": "prasanna",
"description": "watch car's and reels all the time"
}

GET (with id): http://localhost:4000/todos/64ad8f195181e4c971e13312

GET: http://localhost:4000/todos

PUT: http://localhost:4000/todos/64ad8f195181e4c971e1331

DELETE: http://localhost:4000/todos/64ad8f195181e4c971e1331
