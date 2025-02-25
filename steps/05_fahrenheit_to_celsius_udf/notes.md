### Note: 
If you want to run this UDF in Snowflake, other than using the command 
`
SELECT ANALYTICS.FAHRENHEIT_TO_CELSIUS_UDF(35);
`
you need to specify the database like below:
`
SELECT HOL_DB.ANALYTICS.FAHRENHEIT_TO_CELSIUS_UDF(35);
`
