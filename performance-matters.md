## Performance still matters

Be lazy. Only optimize the worst offenders.

### Which metrics matter?
1. Speed Index (how quickly the page contents are visually populated)
2. Time to interactive

#### Synthetic testing
WebPageTest
DevTools network tab
Performance tab

Real User Monitoring
* Navigation Timing API
* Resource Timing API
* User Timing API for custom timings

Optimize for the device and network your users have
Images account for 39-43% of the byes on avg needed to load a webpage.
#### Image optimization toolbox
* ImageOptim
* Look into newer image formats like .webp

Optimizing time to interactive
* analyze bundles
* code-splitting, pre-caching, lazy loading
* minify
* compress
* remove unused code

#### The Cost of Unnecessary Transpiling