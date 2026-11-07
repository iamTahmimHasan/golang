# Go Minimal Web Server

A lightweight web server built using Go's standard `net/http` library. This project demonstrates basic HTTP routing, serving text and HTML responses, and handling simple form submissions without relying on any third-party frameworks.

## Features

- Zero external dependencies (built entirely with the Go standard library).
- Minimal overhead and fast execution.
- Clear demonstration of basic HTTP routing and request handling.

## Routes

| Method     | Endpoint | Description                                          |
| :--------- | :------- | :--------------------------------------------------- |
| `GET`      | `/`      | Serves the main landing page or welcome message.     |
| `GET`      | `/hello` | Returns a simple greeting.                           |
| `GET/POST` | `/form`  | Serves an HTML form and handles the form submission. |

## Prerequisites

- [Go](https://golang.org/dl/) (version 1.18 or higher)
- A terminal or command line interface

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/iamTahmimHasan/golang.git
cd golang
```
