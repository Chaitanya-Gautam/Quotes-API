# Quotes API

Welcome to the Quotes API! This simple API provides a collection of inspiring quotes along with their authors. Feel free to use this API to retrieve motivational quotes for your applications or projects.

## Endpoints

### Get All Quotes

- **URL**: `https://github.com/Chaitanya-Gautam/Quotes_API`
- **Method**: `GET`
- **Description**: Retrieve a list of all quotes available in the API.

#### Example

```bash
curl https://your-api-domain.com/quotes
```

### Quote Structure

Each quote in the API is represented as a JSON object with the following structure:

```json
{
  "text": "The text of the quote.",
  "author": "The author of the quote."
}
```

## Usage

You can integrate this API into your application by making HTTP requests to the provided endpoints. The API is hosted on [GitHub Pages](https://pages.github.com/), and the base URL is `https://your-username.github.io/your-repo`.

### Example Usage (JavaScript):

```javascript
// Fetch all quotes
fetch('https://github.com/Chaitanya-Gautam/Quotes_API/Quotes')
  .then(response => response.json())
  .then(quotes => {
    console.log(quotes);
    // Use the quotes in your application
  })
  .catch(error => console.error('Error fetching quotes:', error));
```
