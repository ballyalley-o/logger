> Module

# Logger

This module provides a custom logger for your application. It uses the 'colors' package to colorize console output for better readability.

## Usage

Import the logger into your file:

```typescript
import logger from './logger'

custom(color: any, ...message: string[]): Logs a custom message with the specified color.
log(...message: string[]): Logs a message in yellow.
info(...message: string[]): Logs an informational message in cyan.
warn(...message: string[]): Logs a warning message in yellow.
tbl(...message: any[]): Logs a table for arrays and objects.
error(...message: string[]): Logs an error message in red.
debug(...message: string[]): Logs a debug message in red.
req(req, res): Logs request details.
server(port: any, apiRoot: any, isProd: boolean, isConnected: boolean): Logs server details.
db(host: any, dbName: any, isConnected: boolean): Logs database details.

```

## Example

```typescript
import logger from './logger'

logger.log('Hello, world!')

logger.info('This is an informational message.')
```

<br/>

## Credits

This module makes use of the following open-source packages:

- [Colors](https://www.npmjs.com/package/colors): Used to colorize console output for better readability.
- [Express](https://www.npmjs.com/package/express): Used to handle HTTP requests and responses.

We are grateful to the authors of these packages for their work.

<br/>

## License

MIT License
