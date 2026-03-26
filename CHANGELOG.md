# Changelog

All notable changes to actinode packages are documented here.

## @actinode/express-activitylog

### v0.2.1 — Latest
- Renamed blacklist → denyList
- Renamed whitelist → allowList
- Updated docs

### v0.2.0
- Added masking support
- denyList for blocking sensitive fields
- allowList for allowing specific fields
- Deep masking for nested objects
- Per model masking configuration
- Manual masking via fluent API .mask()

### v0.1.0
- Initial release
- Express middleware for activity logging
- Fluent API: activity().by().on().log()
- Prisma adapter
- Mongoose adapter

## @actinode/express-permission

### v0.1.0 — Latest
- Initial release
- Role management
- Direct permissions
- Permission groups
- Prisma adapter
- Mongoose adapter
