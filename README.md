# URL Shortener Service
## Endpoints
### POST /shorten
Request:
```json
{ "url": "https://example.com" }
```
Response:
```json
{ "short_url": "http://localhost:8080/abc123" }
```
### GET /abc123
Redirects to the original URL.
## Run Locally
```bash
go run main.go
```
## Contributing
Fork, commit changes, and open a pull request!