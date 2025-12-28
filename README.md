# SubjectivePortfolioEventsDataSource

Subjective datasource implementation for SubjectivePortfolioEventsDataSource.

## Usage

```python
from subjective_datasources.SubjectivePortfolioEventsDataSource import SubjectivePortfolioEventsDataSource

source = SubjectivePortfolioEventsDataSource(params={})
source.fetch()
```

## Parameters

Use the params dictionary when constructing the datasource to provide connection and runtime values.
Refer to get_connection_data() for required fields.
