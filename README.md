# alx-project-0x14

## API Overview
– Brief summary: e.g. “MoviesDatabase lets me search/filter movie titles by year, genre, etc.”

## Version
– e.g. `v1.0` (copy from docs)

## Available Endpoints
– `/titles` – fetch list of titles (supports `year`, `genre`, `page`, `limit`)  
– …any others you spot

## Request & Response Format
– **Request**: REST `GET https://…/titles?year=2025&limit=12&page=1`  
– **Response**:  
  ```json
  {
    "results": [
      {
        "id": "...",
        "titleText": { "text": "Example Movie" },
        "primaryImage": { "url": "…" },
        "releaseYear": { "year": "2025" }
      }, …
    ]
  }
