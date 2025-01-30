# HNG Stage 0 Backend Task (PHP)

## Project Description
This is a public API that returns my registered email, the current datetime in ISO 8601 format, and the GitHub URL of the project.

## Requirements
1. local server


## Setup Instructions
1. Clone the repository to your local server directory
   ```bash
   git clone https://github.com/Meshgenerali/stage0hng.git

2. access the api end point using    http://localhost\stage0/api/index.php

## API Documentation

1. Endpont: Get digitalsolutions.infinityfreeapp.com/
2. Response Format:
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}

3. Exapmle of usage
curl -X GET http://digitalsolutions.infinityfreeapp.com

## Backlink
[HNG PHP Developers](https://hng.tech/hire/php-developers)