# Rust/Rocket/Diesel/Postgres/ Notes Api Project

This is a demo project using Rust, [Rocket](https://rocket.rs/), [diesel](https://diesel.rs/), and Postgres.

### Ensure you are rust nightly complier. Rocket does not work with the stable complier.

## Create a Rocket.toml file and add the following

#### [development]
- port = 3000

 #### [development.databases]
- postgres = { url = "postgres://username:password@localhost:5432/db_name" }
