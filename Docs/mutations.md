# SMIP Mutations

In GraphQL, the endpoint is always the same, but the query payload changes to indicate the response payload you wish to retrieve. Updates and Insertions are called Mutations, and are performed against the same endpoint as queries. For more information on accessing the GraphQL endpoint for your SMIP instance, see the page [SMIP GraphQL Endpoint](smip-graphql.md).

## Example Mutations

**<a name="query-types">Mutating Time Series Sample Values**

The following query payload mutates time series sample values for a given Instance Attribute Tag, with the provided time stamp. If values already exist, they will be updated (replaced). If values did not previously exist, they will be inserted:

```
mutation UpdateData {
  __typename
  replaceTimeSeriesRange(
    input: {
      entries: [
        {value: "19.00", timestamp: "2020-02-25T02:55:25+00:00", status: "0"},
        {value: "21.00", timestamp: "2020-02-25T02:55:20+00:00", status: "0"}
      ],
       tagId: "654"
    }) {
    string
  }
}
```

## Other Operations

Read only operations, called Queries, are performed against the same endpoint. Some  [Query examples can be found here](queries.md).