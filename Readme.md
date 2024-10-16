# MergeX - Automatic GitHub PR Review System

<!--
MergeX is an automated pull request (PR) review system that uses AI to analyze and comment on PRs in GitHub repositories. This project is built with Next.js, Prisma, and integrates with the GitHub API. -->

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Running the Project](#running-the-project)
- [Testing the System](#testing-the-system)
- [Contributing](#contributing)
- [License](#license)

## Features

- GitHub OAuth authentication.
- Automated PR review using AI.
- Webhook for PR triggers.
- Posts AI-generated review comments on PRs.

## Prerequisites

Before setting up the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [PostgreSQL](https://www.postgresql.org/) for the database
- [Prisma](https://www.prisma.io/) for database management
- A [GitHub Developer Account](https://github.com/settings/developers) to create OAuth credentials
