# Hosting
## Hosting is currently only open to a select few while floof is in beta.

## Platforms
- Browser (Currently supported as an option on the site)
- Node.js (Server Environment)
- Bun (Server Environment)

## Connection Options
- Through a routing server (Nothing else needed, is default option)
- Direct connect
    - Requires trusted token
    - Connect to a routing server, but only for management and list
    - Clients directly connect through your server's IP addr

## Accounts
- Not supported on browser no matter what, and no plans to be
- Supported only on trusted direct connect lobbies
    - Strict regulation to ensure no misuse or mistreatment
    - You will be required to host your own account server instance as well
    - Account login is supported via Discord, but you will have to create your own app that follows the guidelines

## API Integration
- Your lobby will still be integrated through the global API for:
    - Basic analytics
    - Player counts
    - Join links
    - Query commands
    - Basic discord bot commands
