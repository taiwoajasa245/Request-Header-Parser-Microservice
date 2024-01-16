# Request Header Parser Microservice

This API provides a system details endpoint which print out the IP address, Language and Software type

## Usage

### Endpoint

GET /api/whoami

### Example

#### Request / Response

```bash
 https://your-app-url/api/whoami

{
  "ipaddress": "0.0.0.0",
  "language": "en-GB,en-US;q=0.9,en;q=0.8",
  "software": "software details"
}

