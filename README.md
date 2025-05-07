# Alpha Vantage API - Delphi
Wrapper written in Delphi to get stock quotes from Alpha Vantage API

## Usage

```
var
  API: TAlphaVantageAPI;
  Stock: TStockQuote;
begin
  API := TAlphaVantageAPI.Create('your-key');
  Stock := API.QuoteEndpoint('APPL');

  // your code

  FreeAndNil(API);
  FreeAndNil(Stock);
end;
```
