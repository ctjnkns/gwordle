# Gwordle
![Gwordle](./example/gwordle.png)

# This is an unofficial personal project.

# Gwordle

A terminal-based Word-esque game written in Go.

## Requirements

- Go 1.26.1 or newer

## Install

### Run without installing

  ```sh
  ### Install locally
  
  git clone git@github.com:ctjnkns/gordle.git
  cd gwordle

  go install .

  Make sure $(go env GOPATH)/bin is on your PATH if needed.

  Then run:

  gwordle

  ## Usage

  gwordle [options]

  ### Options

  - --no-cache re-download the word list
  - --set-word <word> set a specific answer word for debugging
  - --debug enable debug logging
  - -h, --help show help

  ## How to Play

  Guess the hidden 5-letter word in 6 tries.

  After each guess:

  - Green means the letter is in the correct position
  - Yellow means the letter is in the word but in a different position
  - Gray means the letter is not in the word

  ## Examples

  gwordle
  gwordle --no-cache
  gwordle --set-word apple
  gwordle --debug --set-word boost

  ## License

  MIT

