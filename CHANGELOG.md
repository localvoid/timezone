# 0.3.1

- `generate_data_subset` script is removed. It will be available as a
  separate package.

# 0.3.0

- TimeZone database updated to 2015b.
- Removed local location detection heuristics (didn't worked properly).
  Local location is initialized with UTC location by default, use
  `setLocalLocation` to change local location.
- TimeZone database format is changed, data is aligned.

# 0.2.5

- Fixed bug with String formatting (invalid offsets for minutes).

# 0.2.4

- Fixed bug with Calendar-type constructor.

# 0.2.3

- Added `initializeTimeZoneSync` function for standalone environments.
- Fixed bug with script path on Windows.

# 0.2.2

- TimeZone database updated to "2014j".
- "args" and "path" moved from dev dependencies to dependencies.

# 0.2.1

- `tzfile` library renamed to `tzdata`.
- Added `zone1970.tab` parser to `tzdata` library.
- Removed `package:collection` dependency.