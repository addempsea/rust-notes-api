# Rust/Rocket/Diesel/Postgres/ Notes Api Project

This is a demo project using Rust, [Rocket](https://rocket.rs/), [diesel](https://diesel.rs/), and Postgres.

### Ensure you are on rust nightly complier. Rocket does not work with the stable complier.

## Create a Rocket.toml file and add the following

```rust

 [development]
 port = 3000 || your port

 [development.databases]
 postgres = { url = "postgres://username:password@localhost:5432/db_name" }

```
