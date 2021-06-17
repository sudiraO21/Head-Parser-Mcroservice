# [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice)
A Request Header Parser Microservice api project to get IP address, preferred languages (from header Accept-Language) and system infos (from header User-Agent) for your device.

# Installation

```bash
# Install dependencies
$ npm install

# Run the app
$ npm start
```
Access it at localhost:3000


# How to Use

Example Usage:
- [base url]/api/whoami
- [Preview](https://request-header-parser-microservice.freecodecamp.rocks/api/whoami)

Example Output:
```json
{
  "ipaddress": "::ffff:159.20.14.100",
  "language": "en-US,en;q=0.5",
  "software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}
```

---
