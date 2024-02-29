A system that retries and collects data periodically from a source system into a dimensional data store DDS, in a different format.
# DWH main components
`Source Data` => `ETL` => `DDS`
# Why do we store data in a distinct format of the source?
- For better querying to extract insights.
- Tackling various formats of input data, as it's integrate from several sources.
# DWH Uses
- Keeping years of historical data stored and queried for analytical and BI teams.
# DWH Data Retrieval
If `data clening` is evolved in the `ETL` process, there are three options determined by `data quality` rules:
	1. Deleting data.
	2. correcting data
	3. loading data.
# Data Consolidation
As the data in the Dwh is integrated, consolidation should take into account:
1. **the data availability** (some data is available in several systems but not in others).
2. **time ranges** (data in different systems has different validity periods),.
3. **different definitions** (the term total weekly revenue in one system may have a different meaning from total weekly revenue in other sys-tems). 
4. **conversion** (different systems may have a different unit of measure or currency).
5. **matching** (merging data based on common identifiers between different systems).
# OLAP Functionality
1. Drilling down.
2. Slicing.
3. Aggregation.
# See also
[[Appendix]]

