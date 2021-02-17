# WebRequestBot
A JavaScript-powered Discord bot to automate web scraping

## Usage

Commands
 - .req (URL)     
    Shows the default Title of requested page
    
 - .req (URL) (Start HTML) (End HTML)     
    Shows any HTML between the two inputs
    
## Examples

 - `.req https://www.google.com/search?q=test+search&page=1/`

    Returns `test search - Google Search`
    
 - `.req https://youtube.com/Strayfade/ },"subscriberCountText":{"simpleText":" subscribers"},"tvBanner":{"thumbnails":[{"url":"http`

    Returns my current amount of subscribers!
