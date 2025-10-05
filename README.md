# 🕸️ Rust Web Scraper — Extract All Links from a Webpage

A simple asynchronous Rust program that fetches a webpage and prints all hyperlinks (`<a href="...">`) found within it.  
Built using **reqwest**, **select**, and **error_chain**, this project demonstrates web scraping fundamentals in Rust with clean error handling and async execution.

---

## 🚀 Features
- 🌐 Fetches HTML content from any given URL
- 🧠 Parses HTML using the [`select`](https://crates.io/crates/select) crate
- 🔗 Extracts all `<a href="...">` links
- ⚙️ Uses `error_chain` for easy error management
- ⚡ Runs asynchronously with `tokio`

---

## 🧩 Dependencies
This project uses:
- [`reqwest`](https://crates.io/crates/reqwest) — async HTTP client
- [`select`](https://crates.io/crates/select) — HTML document parser
- [`error-chain`](https://crates.io/crates/error-chain) — simplified error handling
- [`tokio`](https://crates.io/crates/tokio) — async runtime
