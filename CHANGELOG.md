# 0.0.3-beta3 - 1-15-2020

## Changed

- Get-UAJob now supports paging, server-side filtering and sorting 
- UA dashboard active and historical job grids now use server-side processing
- Fixing an issue where an AppToken would be generated when executing a script even when AppTokens aren't being used. 
- Fixed issue where license activation would run every time the server was started 
- Fixed issue with dot sourcing files (https://github.com/ironmansoftware/universal-automation/issues/73)
- Fixed sorting of the ID column in the job grid (https://github.com/ironmansoftware/universal-automation/issues/46)

# 0.0.3-beta2 - 1-14-2020

## Changed

- Removed the diagrams component from UniversalAutomation.Dashboard so unlicensed UD dashboards will work. 