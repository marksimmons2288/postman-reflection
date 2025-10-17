# API Collections Assignment

## Collection, Environment, and Sending Request
###
1. Set-up Collection: Select the "New" tab, located in the top right corner of the web page, located left of the "Import" tab, this opens a icon screen with multiple tabs. (select the icon that is labeled Collection).
2. Set-up Environment: Located on the right corner of the web page is a "New Environment" tab. Click the tab and select the plus arrow (+), this will open a page with two input fields. (1) with Varible input field and another with Value input filed. The Varible field is for the name of your key surrounded by braces "{{varibleName}} e.g. {{weatherApiKey}} and the Value is the "password" provided by the API source.
3. Sendig Request: To send a "GEt" request, you set up a base_url varible (snake_case), choose the resource you want to use from the API web page, locate and add the endpoint to the base url by enertering the "KEY" in the input field (snake_case), and the "Value" which are both visually displayed on the API page for correct format. Locate and determine form the API page you selected if a "query param or header" is needed for "Autho" to send a successful (200) request.(Normally a header is generic unless otherwise clarified).
4. By setting up the API key varible in the environment, it allows the use of the API varible key across all APIs in the environment.(although I shared the "key" I could not recieve a successful response, it just displayed "API key required")

## Summary of Response
The response displayed the current weather which included dew point, temperature, date, and wind gust.