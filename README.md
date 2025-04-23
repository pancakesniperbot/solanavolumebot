# Link Cloaker for GitHub Pages

This is a simple link cloaker that helps redirect users from Google to your target site through GitHub Pages.

## How to Use

1. Replace the `targetUrl` in `index.html` with your actual destination URL:
```javascript
const targetUrl = 'https://your-destination-site.com';
```

2. Deploy this to your GitHub Pages repository.

3. To create a cloaked link, use the following format:
```
https://your-github-username.github.io/repository-name/?r=YOUR_ENCODED_URL
```

Where `YOUR_ENCODED_URL` is the base64 encoded version of your target URL.

## Example

If your target URL is `https://example.com`, the encoded version would be `aHR0cHM6Ly9leGFtcGxlLmNvbQ==`

So your cloaked link would be:
```
https://your-github-username.github.io/repository-name/?r=aHR0cHM6Ly9leGFtcGxlLmNvbQ==
```

## Features

- Clean, professional-looking landing page
- Delayed redirection to appear more natural
- Support for multiple destination URLs through URL parameters
- Mobile-responsive design
- No visible redirection in the source code

## Security Note

This solution is designed to be simple and effective, but remember that no cloaking method is 100% foolproof. Use responsibly and in accordance with applicable laws and terms of service. 