# HnswConfigDiff

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ef_construct** | **int, none_type** | Number of neighbours to consider during the index building. Larger the value - more accurate the search, more time required to build index. | [optional] 
**full_scan_threshold** | **int, none_type** | Minimal amount of points for additional payload-based indexing. If payload chunk is smaller than &#x60;full_scan_threshold&#x60; additional indexing won&#39;t be used - in this case full-scan search should be preferred by query planner and additional indexing is not required. | [optional] 
**m** | **int, none_type** | Number of edges per node in the index graph. Larger the value - more accurate the search, more space required. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


