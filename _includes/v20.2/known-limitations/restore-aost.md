An object's historical data is not preserved upon `RESTORE`. This means that if an `AS OF SYSTEM TIME` query is issued on a restored object, the query will fail or the response will be incorrect because there is no historical data to query.