# NuCash Test Assignment for Android Front-end Engineers

The task is to develop an Android mobile application.

Please follow the [design](https://www.figma.com/file/J6gmxWjRDQopqWAh6g6XUE/ReactNativeTask?node-id=0%3A1) and draw inspiration from the [prototype](https://www.figma.com/proto/J6gmxWjRDQopqWAh6g6XUE/ReactNativeTask?page-id=0%3A1&node-id=1%3A2&viewport=560%2C665%2C0.9032468199729919&scaling=min-zoom)

Task Description:
- fetch 10 images from NASA [API](https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY&count=10) at the application start up
- allow users to filter fetched images by title
- redirect to the image details page after user clicks on one
- the detail page should display an image, title and explanation

Technical Requirements:
- make use of Android navigation component
- cache data using Room
- use Retrofit
- use Hilt
- application should have tests
- (Optional) add a deep link for any of the detail pages
- (Optional) display notification in case internet is gone
- (Optional) display notification in case internet is back
