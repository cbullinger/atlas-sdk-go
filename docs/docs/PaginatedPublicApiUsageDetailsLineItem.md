# PaginatedPublicApiUsageDetailsLineItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | Pointer to [**[]Link**](Link.md) | List of one or more Uniform Resource Locators (URLs) that point to API sub-resources, related API resources, or both. RFC 5988 outlines these relationships. | [optional] [readonly] 
**Results** | Pointer to [**[]PublicApiUsageDetailsLineItem**](PublicApiUsageDetailsLineItem.md) | List of returned documents that MongoDB Cloud provides when completing this request. | [optional] [readonly] 
**TotalCount** | Pointer to **int** | Total number of documents available. MongoDB Cloud omits this value if &#x60;includeCount&#x60; is set to &#x60;false&#x60;. The total number is an estimate and may not be exact. | [optional] [readonly] 

## Methods

### NewPaginatedPublicApiUsageDetailsLineItem

`func NewPaginatedPublicApiUsageDetailsLineItem() *PaginatedPublicApiUsageDetailsLineItem`

NewPaginatedPublicApiUsageDetailsLineItem instantiates a new PaginatedPublicApiUsageDetailsLineItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedPublicApiUsageDetailsLineItemWithDefaults

`func NewPaginatedPublicApiUsageDetailsLineItemWithDefaults() *PaginatedPublicApiUsageDetailsLineItem`

NewPaginatedPublicApiUsageDetailsLineItemWithDefaults instantiates a new PaginatedPublicApiUsageDetailsLineItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *PaginatedPublicApiUsageDetailsLineItem) GetLinks() []Link`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *PaginatedPublicApiUsageDetailsLineItem) GetLinksOk() (*[]Link, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *PaginatedPublicApiUsageDetailsLineItem) SetLinks(v []Link)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *PaginatedPublicApiUsageDetailsLineItem) HasLinks() bool`

HasLinks returns a boolean if a field has been set.
### GetResults

`func (o *PaginatedPublicApiUsageDetailsLineItem) GetResults() []PublicApiUsageDetailsLineItem`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PaginatedPublicApiUsageDetailsLineItem) GetResultsOk() (*[]PublicApiUsageDetailsLineItem, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PaginatedPublicApiUsageDetailsLineItem) SetResults(v []PublicApiUsageDetailsLineItem)`

SetResults sets Results field to given value.

### HasResults

`func (o *PaginatedPublicApiUsageDetailsLineItem) HasResults() bool`

HasResults returns a boolean if a field has been set.
### GetTotalCount

`func (o *PaginatedPublicApiUsageDetailsLineItem) GetTotalCount() int`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *PaginatedPublicApiUsageDetailsLineItem) GetTotalCountOk() (*int, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *PaginatedPublicApiUsageDetailsLineItem) SetTotalCount(v int)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *PaginatedPublicApiUsageDetailsLineItem) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


