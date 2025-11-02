# Interact BI - DAX Time Intelligence functions
A series of Power BI DAX UDF's to 
Get it on DAX Lib: https://daxlib.org/package/InteractBI.TimeIntelligence/

## InteractBI.TimeIntelligence.SPLY()
For demonstrations see: https://interact.bi/2025/10/solving-sameperiodlastyear-blanks-and-errors/
- Bypasses filter keep behaviour when using a custom calendar. This means that you can use any column in your calendar table outside the calendar configuration (eg descriptive / relative columns) and produce logical results.
- Handles period disputes between calendars more gracefully, allow each filter context to be respected.
- Provides better and customizable results when partial periods are selected, and/or the periods have different lengths.
