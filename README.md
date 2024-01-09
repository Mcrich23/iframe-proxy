# IFrame Proxy

This simple HTML webpage, hosted on GitHub Pages at [https://mcrich23.github.io/iframe-proxy](https://mcrich23.github.io/iframe-proxy), allows you to load an external URL into an iframe by passing the URL as a query parameter in the URL path.

## Usage

1. Open the following link in your web browser: [https://mcrich23.github.io/iframe-proxy/iframe_loader.html?url=](https://mcrich23.github.io/iframe-proxy/iframe_loader.html?url=)

2. Append the URL you want to load as a query parameter named "url".

   Example:
    ```
    https://mcrich23.github.io/iframe-proxy?url=https://example.com
    ```

3. Replace `your_token` with the actual token or value you want to pass as the parameter.

## Security Considerations

- Ensure that the target website allows embedding in iframes due to security policies (CORS).
- Be aware of the potential security risks associated with loading external content in iframes.

## Disclaimer

This is a simple example intended for controlled environments. Use with caution and consider security implications when working with external URLs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
