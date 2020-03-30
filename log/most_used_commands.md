
  - Tail log along with GREP

  `tail -f application.log | grep "isRealTimePrice"`

  `tail -f application.log | grep "isRealTimePrice" | grep MICROSOFT | grep GOOGLE | grep TESLA`

  - ZGREP (Archived Logs)

  `zgrep "2015-11-25 12:22" application.1.log.gz | grep "Response from WeatherService" | grep "Summer" | grep "Winter"
  
 
  
