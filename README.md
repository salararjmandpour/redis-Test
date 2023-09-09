# GitHub Repositories Cache

A simple Node.js application built with Express that fetches and caches GitHub repository data for a given username using Redis.

## Table of Contents

- [GitHub Repositories Cache](#github-repositories-cache)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
    - [Installation](#installation)

## Introduction

This project is a simple web application that allows users to enter a GitHub username and retrieves and caches the number of public repositories associated with that username. It uses Node.js, Express, Redis, and the GitHub API to achieve this functionality.

## Features

- Fetch and cache GitHub repository data for a given username.
- Implement caching using Redis to reduce API calls to GitHub.
- Provides a simple web interface to enter a GitHub username and display the number of repositories.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) installed on your system.
- [Redis](https://redis.io/) installed and running on your system.

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/github-repos-cache.git
   cd github-repos-cache
