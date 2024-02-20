# Ventrata Octo Test Project

You can find the project description here.
https://paper.dropbox.com/doc/Golang-Task-SRHVn4MGthOvIUZS8R1By

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Go 1.16 or higher
- Docker and Docker Compose

### Installing

#### 1. Clone the repository
```
git clone https://github.com/bigrocks918/ventrata_octo.git
cd ventrata_octo
```

#### 2. Build the Docker containers
```
make docker-build
```

#### 3. Start the services
```
make docker-up
```

#### 4. Apply database migrations
```
make migrate-up
```

### Runing Tests
```
make test
```

## Built With
- Go (Golang)
- Docker
- golang-migrate/migrate
- CurrencyAPI
- Data-dog
- sql-mock