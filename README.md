# New API
## Twitter
Not a developer? Join our twitter to see news headlines all accross the world [here](https://twitter.com/sosleafy)
## API
Free news api for you to consume. Top News specific to India, API. Updates with new news every hour.
### See in action
See the JSON in action here:
### For Indian headlines
[https://raw.githubusercontent.com/theroyakash/newsapis/main/india_news.json](https://raw.githubusercontent.com/theroyakash/newsapis/main/india_news.json)
### For US Headlines
[https://raw.githubusercontent.com/theroyakash/newsapis/main/us_news.json](https://raw.githubusercontent.com/theroyakash/newsapis/main/us_news.json)
### For UK Headlines
[https://raw.githubusercontent.com/theroyakash/newsapis/main/us_news.json](https://raw.githubusercontent.com/theroyakash/newsapis/main/uk_news.json)

### Python implementation
```python
import requests

url = 'https://raw.githubusercontent.com/theroyakash/newsapis/main/us_news.json'
content = requests.get(url).json()
print(f"Status: {content['status']}")
```
